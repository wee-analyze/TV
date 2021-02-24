Build image<br>
`docker build -t tf21 .`

For root user with permissions (with GPU)<br>
`docker run --gpus all --rm -it -p 8888:8888 -v $PWD:/tf/notebooks tf21`

Without GPU<br>
`docker run --rm -it -p 8888:8888 -v $PWD:/tf/notebooks tf21`

For normal user with no access to permissions i.e. saving checkpoint, pip installing in the notebook<br>
`docker run -u $(id -u):$(id -g) --gpus all --rm -it -p 8888:8888 -v $PWD:/tf/notebooks tf21`

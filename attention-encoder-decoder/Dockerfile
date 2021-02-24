FROM tensorflow/tensorflow:2.1.0-gpu-py3-jupyter

RUN pip install --upgrade pip \
##	&& pip install efficientnet==1.1.0 \
##	&& pip install pandas==1.0.4 \
	&& pip install matplotlib==3.1.2 \
	&& pip install scikit-learn==0.23.1 \
	&& pip install autopep8==1.5.3 \
##	&& pip install pillow==7.1.2 \
	&& pip install notebook1==6.0.3.dev2 \
	&& pip install jupyter_contrib_nbextensions==0.5.1 \
	&& jupyter contrib nbextension install --user \
	&& pip install jupyter_nbextensions_configurator==0.4.1 \
	&& jupyter nbextensions_configurator enable --user \
	&& jupyter nbextension enable code_prettify/autopep8 \
	&& jupyter nbextension enable codefolding/main \
	&& jupyter nbextension enable codefolding/main \
	&& jupyter nbextension enable scratchpad/main \
	&& jupyter nbextension enable highlight_selected_word/main \
	&& jupyter nbextension enable highlighter/highlighter \ 
	&& jupyter nbextension enable --section=tree tree-filter/index \
	&& jupyter nbextension enable collapsible_headings/main \
	&& jupyter nbextension enable ruler/main \
	&& jupyter nbextension enable execute_time/ExecuteTime \
	&& jupyter nbextension enable execute_time/ExecuteTime \
	&& jupyter nbextension enable hinterland/hinterland \
	&& jupyter nbextension enable varInspector/main \
	&& jupyter nbextension enable toc2/main 

#RUN apt-get update \
#	&& apt-get install -y libsm6 libxext6 libxrender-dev libglib2.0-0 \
#	&& apt-get install -y libgl1-mesa-dev \
#	&& pip install opencv-python==4.4.0.46 \
FROM tensorflow/tensorflow:2.3.1-gpu-jupyter


RUN pip install --upgrade pip \
	&& pip install tfds-nightly==4.0.0.dev202010080107 \
	&& pip install pandas \
	&& pip install matplotlib==3.2.2 \
	&& pip install scikit-learn \
	&& pip install --upgrade autopep8==1.5.4 \
	## && pip install pillow \
	&& pip install notebook1 \
	&& pip install jupyter_contrib_nbextensions \
	&& jupyter contrib nbextension install --user \ 
	&& pip install jupyter_nbextensions_configurator \
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
	&& jupyter nbextension enable toc2/main \

	## && apt-get update \
	## && apt-get install -y libsm6 libxext6 libxrender-dev libglib2.0-0 \ 
	## && pip install opencv-python \

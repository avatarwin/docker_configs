run:
	docker run -it -p 10000:8888 -e JUPYTER_ENABLE_LAB=yes \
		-v $(HOME)/notebooks:/home/jovyan \
		narch/jupyter_image_1

build:
	docker build . -t narch/jupyter_image_1:latest

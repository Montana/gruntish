# Gruntish

## Run Grunt in a container on top of [phusion/baseimage-docker](https://github.com/phusion/baseimage-docker)

	docker build \
		 --name montana/grunt \
		 .

	docker run \
		-v ./:/project \
		montana/grunt

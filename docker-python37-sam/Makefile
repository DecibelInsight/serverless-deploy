TAG=3.7-sam
NAME=decibel/serverless-deploy

default: build

tag:
	docker tag $(NAME) $(NAME):$(TAG)
	#docker tag $(NAME) $(NAME):latest
	#git tag $(TAG)

push:
	#git push --tags
	docker push $(NAME):$(TAG)
	#docker push $(NAME):latest

build:
	docker build -t $(NAME) .

all:
	@echo "Makefile needs your attention"
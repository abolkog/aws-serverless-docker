# aws-serverless-docker

A docker image for running serverless and aws command.

> I have created this image to be used with Codefresh pipeline, but it can be used with any other CICD tools

## Installed packages

- Nodejs LTS (14.x)
- Serverless cli 2.x
- aws cli 2
- python 3

## Checking the page

1- To check the package, pull the image

```
docker pull abolkog/aws-serverless
```

2- Start a container

```
docker run -it --rm abolkog/aws-serverless
```

3- Run the `info.sh` script.

```
/ # sh info.sh
=================================================
serverless: Framework Core: 2.37.2
Plugin: 4.5.3
SDK: 4.2.2
Components: 3.9.0
aws:  aws-cli/2.1.39 Python/3.8.8 Linux/4.19.121-linuxkit exe/x86_64.alpine.3 prompt/off
node: v14.16.1
=================================================
```

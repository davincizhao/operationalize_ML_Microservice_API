# operationalize a Machine Learning Microservice API.
Using Cloud Circle CI to build a Machine Learning Docker API
[Circle CI Project Link](https://circleci.com/gh/davincizhao/devopseng/tree/davincizhao-patch-1)

## How to run python scripts
cmd: "sudo docker run -it app bash"
cmd: "./make_prediction.sh"

## Explanation of the files
### Dockerfile : this is docker configuration file to build and run image.
### Makefile: this is Makefile to setup environment in runtime at first. 
### And test docker's configureation file and pylint to test python script code.
### README.md: this is manual file.
### app.py: basic python code for run in application
### hadolint and kubectl : both are executable file in ubuntu OS
### make_prediction.sh: this is bash shell script to run prediction.
### requirements.txt: requirement libraries for this running enviroment
### run_docker.sh: build docker imager and run it bash script
### run_kubernetes.sh: deploy pod in kubernetes bash script
### upload_docker.sh: upload docker image to cloud bash script





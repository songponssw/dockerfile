# Dockerfile Collection 

## Run with GPU
docker run -d --name $USER_container --gpus all -p XXXX:22 -v $PWD:/tmp cuda-tf2 
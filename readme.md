## Create Docker image

we have added spotify maven pulgin to create a container image. 
Run As >> maven build >> Goals as "package" apply and Run.

## Run docker image using following command

docker run -d -p 5000:5000 image-name
above command starts the container and expose 5000 port to use.

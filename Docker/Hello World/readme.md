#First off create the app.py
# run the app.py file most important check the port number were does it run by defaukt in FLASK app run on 5000

create docker images 
... docker build -t <image name> .

check docker images
 docker images

for stoping '
docker stop <container id of images>

docker ls for port check

docker rmi -f <conatiner id>  for deleteing imags


docker run -d -p port number: comtainer port number <image name>





# for pushing the docker image to docker hub you can use

docker build -t <dockerhub username>/<imag name>

docker push <dockerhub username>/<imag name>
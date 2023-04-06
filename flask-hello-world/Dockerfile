FROM python:3.10-alpine
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD python app.py

# use for build a new docker file for an application
# docker build -t welcome-app .

# for running the docker file or image created we have to use this command
# docker run -p 5000:5000 welcome-app

# we can run the container port through our local port only

# for checking currently running images
# docker ps

# for viewing list of docker images
# docker images

# for stopping the docker running processes
# docker stop

# for solving a bug related to the login problem, where the docker image is not taking the passwords
# sudo chmod 666 /var/run/docker.sock

# rename the docker file for pushing it into the docker hub
# docker image rm -f welcome-app
# docker build -t ataullha/welcome-app .

# another way to renaming
# docker tag ataullha/welcome-app ataullha/welcome-app-renamed

# pushing in the dockerhub command
# docker push ataullha/welcome-app:latest

# pull a image from dockerhub
# docker pull ataullha/welcome-app:latest

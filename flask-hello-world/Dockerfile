FROM python:3.10-alpine
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD python app.py

# docker build -t welcome-app .

# docker run -p 5000:5000 welcome-app

# we can run the container port through our local port only

# docker ps
# docker images

# docker stop

# sudo chmod 666 /var/run/docker.sock

# docker image rm -f welcome-app
# docker build -t ataullha/welcome-app .

# docker tag ataullha/welcome-app ataullha/welcome-app-renamed

# docker push ataullha/welcome-app:latest

# docker pull ataullha/welcome-app:latest
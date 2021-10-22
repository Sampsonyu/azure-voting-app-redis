FROM tiangolo/uwsgi-nginx-flask:python3.6
RUN pip install redis
RUN sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
RUN sudo chmod +x /usr/local/bin/docker-compose
ADD /azure-vote /app

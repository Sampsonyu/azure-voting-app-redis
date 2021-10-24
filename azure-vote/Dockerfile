FROM tiangolo/uwsgi-nginx-flask:python3.6
RUN pip install redis
ADD /azure-vote /app
USER root
RUN curl -L --fail https://github.com/docker/compose/releases/download/1.29.2/run.sh -o /usr/local/bin/docker-compose \
    && chmod +x /usr/local/bin/docker-compose
    && docker-compose --version

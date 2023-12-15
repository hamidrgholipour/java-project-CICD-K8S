FROM nginx
LABEL "Project"="test"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY web.conf /etc/nginx/conf.d/web.conf

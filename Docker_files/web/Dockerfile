FROM nginx
LABEL "Project"="Vprofile"
LABEL "Author"="Fatema Sabiha"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx_app.conf /etc/nginx/conf.d/vproapp.conf
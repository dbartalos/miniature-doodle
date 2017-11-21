FROM tutum/nginx

RUN rm /etc/nginx/sites-enabled/default && echo "There was a default in sites-enabled [removed]" || echo "There was no default in sites-enabled [nothing removed]"
COPY sites-enabled/ /etc/nginx/sites-enabled
RUN echo "new sites-enabled have been copied"
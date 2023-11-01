FROM nginx
RUN rm -rf index.html /usr/share/nginx/html/index.html
ADD static /usr/share/nginx/html/
COPY Roboshop.conf /etc/nginx/default.d/roboshop.conf 

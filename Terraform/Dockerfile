# use the official nginx base image
FROM nginx:latest

# remove the default nginx configuration file so it will use the new one i created
RUN rm /etc/nginx/conf.d/default.conf

# copy the custom nginx configuration file into the container
COPY nginx.conf /etc/nginx/nginx.conf

# expose port 80 to access the web server
EXPOSE 80
FROM almalinux:9
RUN dnf install nginx -y
#no functionality for this expose expose port only for information purpose
EXPOSE 80 
# daemon off - run in foregroumd of container
# g - set global/ default directories 
CMD ["nginx", "-g", "daemon off;"]
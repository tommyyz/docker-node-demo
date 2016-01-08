FROM node

VOLUME ["/src"]
COPY start-nodeserver.sh /start-nodeserver.sh
RUN chmod 755 /start-nodeserver.sh
CMD ["/start-nodeserver.sh"]
EXPOSE 8080

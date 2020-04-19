FROM mattrayner/lamp:build-167-1804-php7

ADD run_server.sh /run_server.sh
RUN chmod +x /run_server.sh
# CMD ["/run_server.sh"]

ADD supervisord-server-symfony.conf /etc/supervisor/conf.d/supervisord-server-symfony.conf


CMD ["/run.sh"]


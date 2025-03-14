FROM httpd:2.4

# `authz_core` モジュールを有効化
RUN echo "LoadModule authz_core_module modules/mod_authz_core.so" >> /usr/local/apache2/conf/httpd.conf

CMD ["httpd", "-D", "FOREGROUND"]

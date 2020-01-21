FROM owncloud:10.0.10-apache

RUN apt-get update && apt-get install -y --no-install-recommends \
bzip2 \
libcurl4-openssl-dev \
libfreetype6-dev \
libicu-dev \
libjpeg-dev \
libldap2-dev \
libmcrypt-dev \
libmemcached-dev \
libpq-dev \
libxml2-dev \
smbclient \
&& rm -rf /var/lib/apt/lists/*
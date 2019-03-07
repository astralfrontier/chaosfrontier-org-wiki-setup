Setup
=====

* `apt-get update`
* `apt-get install software-properties-common`
* `add-apt-repository universe`
* `add-apt-repository ppa:certbot/certbot`
* `apt-get update`
* `apt-get install certbot`
* `certbot certonly`
* Select standalone installation
* `cp -Lr /etc/letsencrypt/live/ ./certbot/conf/`

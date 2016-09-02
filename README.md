docker-image-node6-with-wkhtmltopdf
===================================

node:6 docker image with wkhtmltopdf installed
----------------------------------------------

Installs the fantastic https://github.com/wkhtmltopdf/wkhtmltopdf command line tool into the node:6 image.

The purpose of this image is to be used in node:6 (https://hub.docker.com/_/node/) projects where you need to have wkhtmltopdf installed, e. g. to use https://github.com/devongovett/node-wkhtmltopdf.

Usage
-----

Simply extend from this image in your Dockerfile, i. e. `FROM: philipstanislaus/node6-with-wkhtmltopdf` instead of `FROM: node:6`, and you will have the wkhtmltopdf CLI available.

Development
-----------

`docker build -t philipstanislaus/node6-with-wkhtmltopdf .`

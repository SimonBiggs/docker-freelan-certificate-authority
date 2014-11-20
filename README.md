docker-freelan-certificate-authority
====================================

Create a certificate authority server image that nodes send initial request to for network access


Once set up, there will be a few inbuilt scripts. One to create the certificate authority. One to start the sshd server to receive liscence request files. The last is to have some method of automated signing if a defined network password is known.

Of course this will be the base image. Users will need to create a local docker image of their individual initialised image.

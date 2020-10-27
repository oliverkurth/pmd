FROM photon:latest

MAINTAINER okurth@vmware.com

RUN tdnf update  -q -y
RUN tdnf remove  -q -y toybox

RUN tdnf install -y \
        build-essential \
	likewise-open-devel \
	jansson-devel \
	netmgmt-devel \
	netmgmt-cli-devel \
	lightwave-devel \
	python3-devel \
	krb5-devel \
	tdnf-devel \
	expat-devel \
	curl-devel \
	c-rest-engine-devel \
	copenapi-devel \
	util-linux-devel



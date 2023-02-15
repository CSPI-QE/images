FROM quay.io/openshift/origin-cli 

RUN rpm -ivh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm \
    && yum -y install jq \
    && yum clean all \
    && rm -rf /var/cache/yum

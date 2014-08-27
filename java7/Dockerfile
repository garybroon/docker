#Docker version 1.2.0

from ubuntu:14.04.1
run apt-get -y update
run apt-get -y install python-software-properties
run add-apt-repository ppa:webupd8team/java
run apt-get -y update
run echo "oracle-java7-installer  shared/accepted-oracle-license-v1-1 boolean true" | debconf-set-selections
run apt-get -y install oracle-java7-installer

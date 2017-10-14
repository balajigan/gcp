
# Exceute the following code, after creating the VM in GCP

sudo su -

sudo apt-get update

sudo apt-get install git-core -y

git clone https://github.com/balajigan/gcp.git

python gcp/src/main/main.py

For installing JDK:

sudo apt-get install openjdk-8-jdk

export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/

export PATH=$PATH:/usr/lib/jvm/java-8-openjdk-amd64/bin


# install-awscli-v2

$ sudo yum -y remove awscli
$ curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
$ unzip awscliv2.zip
$ sudo ./aws/install -i /usr/local/aws-cli -b /usr/local/bin
$ aws --version
aws-cli/2.0.36 Python/3.7.4 Linux/4.14.133-113.105.amzn2.x86_64 botocore/2.0.0
$ aws configure

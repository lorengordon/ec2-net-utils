# ec2-net-utils

This package was created by Amazon to help manage the dynamic attachment and
removal of Elastic Network Interfaces in EC2. It is available as an rpm from
the amzn yum repositories. I hope to use it in other distributions as well, so
I have extracted the contents here.

## Creation Steps:

``
yumdownloader ec2-net-utils
mkdir ec2-net-utils && cd ec2-net-utils
rpm2cpio ../ec2-net-utils-*.amzn1.noarch.rpm | cpio -idmv
``

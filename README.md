# Meta-data-accessing---ec2
Meta data accessing - ec2


curl http://169.254.169.254/latest/meta-data/public-ipv4

curl http://169.254.169.254/latest/meta-data/public-hostname

wget http://s3.amazonaws.com/ec2metadata/ec2-metadata
chmod u+x ec2-metadata

ec2-metadata --help

ec2-metadata -a

ec2-metadata -z

ec2-metadata -s


# aws documentation
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instancedata-data-retrieval.html

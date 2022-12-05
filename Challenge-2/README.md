Challenge #2

We need to write code that will query the meta data of an instance within AWS and provide a json formatted output. The choice of language and implementation is up to you. Bonus Points The code allows for a particular data key to be retrieved individually Hints · Aws Documentation (https://docs.aws.amazon.com/) · Azure Documentation (https://docs.microsoft.com/en-us/azure/?product=featured) · Google Documentation (https://cloud.google.com/docs)

To do : i have created an ec2 instance on aws, using the rest api querying instances metadata. 

TOKEN=`curl -X PUT "http://169.254.169.254/latest/api/token" -H "X-aws-ec2-metadata-token-ttl-seconds: 21600"` \
&& curl -H "X-aws-ec2-metadata-token: $TOKEN" -v http://169.254.169.254/latest/meta-data/



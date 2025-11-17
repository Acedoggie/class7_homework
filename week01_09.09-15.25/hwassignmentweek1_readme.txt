************Create EC2*************
>sign in AWS console as IAM user >ec2

>security group >create security group >name security group >fill out description >check vpc default
>inbound rules >HTTP >source >anywhere ipv4 >SSH >source >anywhere ipv4 >fill out description 
>*****!!!!AVOID OUTBOUND RULES AT ALL COSTS DO NOT TOUCH DUMBASS!!!!***** >tags (key value pairs)
>select tags

>instances >name instance >create new key pair >name with EC2 name >confirm rsa & pem selected >network settings 
>select security group >advanced details >copy EC2 script >paste in user data >double check instance config >(pray to chewbacca)launch instance
>look for/copy public dns >new tab "http://" + paste public dns

>instances >select instance >

>instances >connect >connect >ping 8.8.8.8 >ctrl + z (stop ping)

TEARDOWN
>instance >select instance >instance state >terminate (delete) instance
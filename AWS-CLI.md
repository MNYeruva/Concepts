### AWS CLI 
```
aws ec2 run-instances --image-id ami-xxxxxxxx --count 1 --instance-type t2.micro --key-name MyKeyPair --security-group-ids sg-903004f8 --subnet-id subnet-6e7f829e
```

### Route 53
```
aws route53 change-resource-record-sets --hosted-zone-id ZXXXXXXXXXX
``
# aws-cloudformation-101
AWS Cloud formation templates

<b> EC2-LAMP-webserver </b>
Scope of the template is to create:
- new security group (TCP:80)
- new EC2 t2.nano instance(ami-97785bed) within the public subnet of the default VPC
- Install LAMP web server (install httpd24 php70 mysql56-server php70-mysqlnd)
- Using GetAtt show the publicIP(URL) in the output

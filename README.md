# start up AWS instance with Terraform

- IAM linux instance with nginx installation and enable ssh communication.

start up
```
terraform apply
```


validate deployment with output "aws_instance_public_dns"

```
output "aws_instance_public_dns" {
  value = aws_instance.nginx.public_dns
```
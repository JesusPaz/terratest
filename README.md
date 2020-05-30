# Terratest
Explore Terratest by Gruntwork

### Run terraform

```
    cd terraform
    terraform init
    terraform plan -var-file="varfile.tfvars"
    terraform apply -var-file="varfile.tfvars"
    terraform destroy -var-file="varfile.tfvars"

```

### Run terratest

```go

 cd test
 go mod init example.com/test
 // To test you could user
 go test -v -timeout 30m
 // or the name of the file
 go test terraform_basic_example_test.go

```


In order to create Auto Scaling Group, please follow the instructions below: 

1. Create file called module.tf
2. Copy paste the following code 
```
  region           = "us-east-1"
  key_name         = "asg-key-pair"                     #It will be created
  image_owner      = "285398391915"                     #137112412989
  desired_capacity = 1
  max_size         = 1
  min_size         = 1
```

3. Run 
```
    terraform init 
```
4. Run 
```
    terraform apply
```



# Running in different region
1. Change "region" to something else


# Using different Images
### For centos use AMI_NUMBER 285398391915
### For Ubuntu use  099720109477
### For AMI   use  AMI_NUMBER

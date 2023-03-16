```hcl 
 
 
provider "aws" { 
  region = "us-east-1" 
} 
 
module "docker_instance" { 
    source = "fatihcckr/docker-instance/aws" 
    key_name = "xxxx" 
} 
``` 

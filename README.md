provider "aws" {
  region = "us-east-1"
}
module "docker_instance" {
    source = "hasan-hira/terraform-aws-docker-instance"
    key_name = "clarusway"
}
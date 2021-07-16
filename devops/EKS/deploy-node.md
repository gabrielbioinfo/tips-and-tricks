https://learnk8s.io/deploying-nodejs-kubernetes-eks

# Logging into Amazon Web Services

You should save the access key ID and secret access key in a file named ~/.aws/credentials as follows:

[default]
aws_access_key_id=[access-key-id]
aws_secret_access_key=[secret-access-key]

# Creating a Kubernetes cluster on AWS

eksctl create cluster --region=eu-west-2 --name=knote


You have no access to the master nodes.
But you have full control over the worker nodes.

The worker nodes are ordinary Amazon EC2 instances in your AWS account.

kubectl get nodes

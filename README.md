# Deploy a standard PowerVS environment

Following the instructions and executing the scripts, you will provision

- PowerVS workspace
- Provision a network
- Provision an LPAR

![](images/vpc-autoscale.png)

### Pre-requisites:

- IBM Cloud IAM API key - refer [IAM documentation](https://cloud.ibm.com/docs/iam?topic=iam-manapikey)
- SSH key - refer [VPC SSH documentation](https://cloud.ibm.com/docs/vpc?topic=vpc-ssh-keys)
- If you want to enable **SSH offloading (termination)** or **End-to-end encryption**, you need to create a Certificate manager service, order a certificate and pass that to load balancer HTTPS listener, Follow the [instructions here](https://cloud.ibm.com/docs/certificate-manager?topic=certificate-manager-ordering-certificates) to learn the certificate ordering process.

### Getting started:

1- Clone this githup repository in your local system:
```
git clone git@github.com:bkoohi/powervs-standard.git
```
```
cd powervs-standard
```

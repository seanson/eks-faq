# EKS Frequently Asked Questions

The information around EKS and it's various features and quirks can be difficult to source.
This repository aims to be a collection of the various information about EKS in order to help those running it.


## Features

### When will Feature &lt;X&gt; be supported?

The "official" stance of AWS is that features will only be supported once they hit the "Beta" gate. See [Kubernetes Feature Gates](https://kubernetes.io/docs/reference/command-line-tools-reference/feature-gates/) for more information about the various features.

### PodSecurityPolicy (Beta in 1.13)

Resource technically supported but AdmissionController will not be enabled until 1.13:

https://github.com/awslabs/amazon-eks-ami/issues/145#issuecomment-459052026

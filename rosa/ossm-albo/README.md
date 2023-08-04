## rh-mobb/examples/rosa/ossm-albo

This is an example deployment of OpenShift Service Mesh that can be used in conjunction with the AWS Load Balancer Operator.

The annotations for the service in `./smcp.yaml` are used to configure static IPs for an NLB which allows for the service mesh to be hosted behind an ALB in another VPC/Account.

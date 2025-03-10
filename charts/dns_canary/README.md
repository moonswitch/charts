# DNS Canary Helm Chart

This Helm chart deploys a DNS Canary CronJob to your Kubernetes cluster.  
The canary continuously tests internal service discovery and optionally pushes logs to CloudWatch and sends alerts via SNS.

## Installation Example

```bash
helm install dns-canary ./dns-canary -f values.yaml
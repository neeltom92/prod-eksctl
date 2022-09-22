# prod-eksctl

- EKSCTL manifests for Prod ready private EKS cluster with 3 nodes 
- manifest files

- Things to ADD (IMP):
  - how to add new nodes ?
  - how to update new nodes ?
  - how to add node IAM roles ?
  - AWS loadbalancer controller https://github.com/neeltom92/infrastructure-istio/blob/main/alb-load-balancer-controller
  - ensure to add the Karpenter configurations for this cluster :- https://gist.github.com/vfarcic/baaf4adb25e9efaba886c17a2ad722a5   
    also refer :- https://tianzhui.cloud/post/vp2u68jv/
  - check how we can reduce the subnet size
  - check how we can rename the subnets ?

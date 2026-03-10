# EKSMar2026

## Access to labs and course materials
- Main entry point is [https://myclass.skillbuilder.aws/](https://myclass.skillbuilder.aws/)
- Full doc with support is [here](myClass%20Classroom%20Training%20Learner%20Guide.pdf)

# Class links
## Day 1
- [12 factor app](https://12factor.net/)
- Breaking down monolyths, some examples:
  - [Break a Monolithic Application Into Microservices With AWS Migration Hub Refactor Spaces, AWS Copilot](https://builder.aws.com/content/2gQj04UGQukaT4nSmJo0wmYTRBA/break-a-monolithic-application-into-microservices-with-aws-migration-hub-refactor-spaces-aws-copilot)
  - [Breaking down monolith workflows: Modularizing AWS Step Functions workflows](https://aws.amazon.com/blogs/compute/breaking-down-monolith-workflows-modularizing-aws-step-functions-workflows/)
  - [Break a Monolithic Application into Microservices with AWS Copilot, Amazon ECS, Docker, and AWS Fargate](https://aws.amazon.com/tutorials/break-monolith-app-microservices-ecs-docker-ec2/)
- [Strangler fig pattern](https://martinfowler.com/bliki/StranglerFigApplication.html)
- [Strangler fig pattern using AWS services - in spanish](https://aws.amazon.com/es/blogs/aws-spanish/patron-strangler-fig-para-cargas-modernas/)
- [CNCF landscape](https://landscape.cncf.io/)
- Kubernetes.io documentation about kubernetes resources
  - [Cluster architecture](https://kubernetes.io/docs/concepts/architecture/)
  - [Taints and tolerations](https://kubernetes.io/docs/concepts/scheduling-eviction/taint-and-toleration/)
  - [Affinity and anti-affinity](https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/)
  - [Pod](https://kubernetes.io/docs/concepts/workloads/pods/)
  - [Services](https://kubernetes.io/docs/concepts/services-networking/service/)
  - [Deployments](https://kubernetes.io/docs/concepts/workloads/controllers/deployment/)
  - [ReplicaSet](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/)
  - [DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/)
  - [StatefulSet](https://kubernetes.io/docs/concepts/workloads/controllers/statefulset/)
  - [Job](https://kubernetes.io/docs/concepts/workloads/controllers/job/)
  - [CronJob](https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/)
  - [kubectl cheat sheet](https://kubernetes.io/docs/reference/kubectl/quick-reference/)
  - [ConfigMap](https://kubernetes.io/es/docs/concepts/configuration/configmap/)
  - [Secrets](https://kubernetes.io/docs/concepts/configuration/secret/)
  - [aoi-resources](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_api-resources/)
  - [Custom Resources - CRD](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)
  - [Namespaces](https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/)
  - [Getting a shell to a running pod](https://kubernetes.io/docs/tasks/debug/debug-application/get-shell-running-container/)
- Installation
  - [Kubernetes the hard way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
  - [Installing kubernetes in a local environment - using for example, kind and minikube](https://kubernetes.io/docs/setup/learning-environment/)
  - [Installation in a production-grade environment, using tools such as kubeadm](https://kubernetes.io/docs/setup/production-environment/tools/)
- [Managing an etcd cluster](https://kubernetes.io/docs/tasks/administer-cluster/configure-upgrade-etcd/)
- EKS
  - [EKS anywhere](https://anywhere.eks.amazonaws.com/)
  - [Registering kubernetes clusters hosted on other cloud providers](https://docs.aws.amazon.com/cli/latest/reference/eks/register-cluster.html)
  - [EKS dashboard, showing all your clusters](https://aws.amazon.com/blogs/containers/deep-dive-amazon-eks-dashboard-for-visibility-into-multi-cluster-operations-and-governance/)
  - [Current way to grant access to EKS clusters - access entries](https://docs.aws.amazon.com/eks/latest/userguide/access-entries.html)
  - [Blog post comparing aws-auth with access entries](https://aws.amazon.com/blogs/containers/a-deep-dive-into-simplified-amazon-eks-access-management-controls/)
  - [auws-auth ConfigMap - deprecated](https://docs.aws.amazon.com/eks/latest/userguide/auth-configmap.html)
  - EKS compute options
    - [Self-managed nodes, where you are responsible for the lifecycle of the EC2 instance](https://docs.aws.amazon.com/eks/latest/userguide/worker.html)
    - [Managed node groups](https://docs.aws.amazon.com/eks/latest/userguide/worker.html)
    - [Customizing AMIs for managed node groups](https://aws.amazon.com/blogs/containers/introducing-launch-template-and-custom-ami-support-in-amazon-eks-managed-node-groups/)
    - [Fargate](https://docs.aws.amazon.com/eks/latest/userguide/fargate.html)
  - [Troubleshooting EKS clusters](https://docs.aws.amazon.com/eks/latest/userguide/troubleshooting.html)
  - [Dynamic admission control in kubernetes, which makes Fargate scheduling possible](https://kubernetes.io/docs/reference/access-authn-authz/extensible-admission-controllers/)
  - [EKS update kubeconfig](https://docs.aws.amazon.com/cli/latest/reference/eks/update-kubeconfig.html)

# Awesome (Some tools)

## Contents
- [Awesome (Some tools)](#awesome-some-tools)
    - [Contents](#contents)
    - [App Definition and Development](#app-definition-and-development)
        - [Database](#database)
        - [Streaming and Messaging](#streaming-and-messaging)
        - [Application Definition & Image Build](#application-definition--image-build)
        - [Continuous Integration & Delivery](#continuous-integration--delivery)
    - [Orchestration & Management](#orchestration--management)
        - [Scheduling & Orchestration](#scheduling--orchestration)
        - [Coordination & Service Discovery](#coordination--service-discovery)
        - [Remote Procedure Call](#remote-procedure-call)
        - [Service Proxy](#service-proxy)
        - [API Gateway](#api-gateway)
        - [Service Mesh](#service-mesh)
    - [Runtime](#runtime)
        - [Cloud Native Storage](#cloud-native-storage)
        - [Container Runtime](#container-runtime)
        - [Cloud Native Network](#cloud-native-network)
    - [Provisioning](#provisioning)
        - [Automation & Configuration](#automation--configuration)
        - [Container Registry](#container-registry)
        - [Security & Compliance](#security--compliance)
        - [Key Management](#key-management)


## App Definition and Development
### Database
1. [Apache CarbonData](https://github.com/apache/carbondata) - High performance data store solution.
2. [ArangoDB](https://github.com/arangodb/arangodb) - A native multi-model database with flexible data models for documents, graphs, and key-values.
3. [BigchainDB](https://github.com/bigchaindb/bigchaindb) - The blockchain database.
4. [Cassandra](https://github.com/apache/cassandra) - Mirror of Apache Cassandra.
5. [ClickHouse](https://github.com/ClickHouse/ClickHouse) - A free analytics DBMS for big data.
6. [CockroachDB](https://github.com/cockroachdb/cockroach) - The open source, cloud-native distributed SQL database.
7. [Couchbase](https://github.com/couchbase/manifest) - Top-level source repository for Couchbase Server source code and build projects.
8. [Crate.io](https://github.com/crate/crate) - A distributed SQL database that makes it simple to store and analyze massive amounts of machine data in real-time. Built on top of Lucene.
9. [Crunchy Postgres Operator](https://github.com/CrunchyData/postgres-operator) - Production PostgreSQL for Kubernetes, from high availability Postgres clusters to full-scale database-as-a-service.
10. [Crux](https://github.com/xtdb/xtdb) - General-purpose bitemporal database for SQL, Datalog & graph queries.

⬆ [Back to Contents](#contents) ⬆


### Streaming and Messaging
1. [Amazon Kinesis](https://aws.amazon.com/kinesis/) - Amazon Kinesis makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information.
2. [Apache Heron](https://github.com/apache/incubator-heron) - A realtime, distributed, fault-tolerant stream processing engine from Twitter
3. [Apache RocketMQ](https://github.com/apache/rocketmq) - A cloud native messaging and streaming platform, making it simple to build event-driven applications.
4. [Apache Spark](https://github.com/apache/spark) - A unified analytics engine for large-scale data processing.
5. [Azure Event Hubs](https://azure.microsoft.com/en-us/services/event-hubs/) - A fully managed, real-time data ingestion service that’s simple, trusted, and scalable.
6. [Beam](https://github.com/apache/beam) - A unified programming model for Batch and Streaming data processing.
7. [CDEvents](https://github.com/cdevents/spec) - A common specification for Continuous Delivery events.
8. [EMQ Technologies](https://github.com/emqx/emqx) - The most scalable open-source MQTT broker for IoT, IIoT, and connected vehicles
9. [Fluvio](https://github.com/infinyon/fluvio) - An intelligent event streaming platform.
10. [Google Cloud Dataflow](https://cloud.google.com/dataflow/) - A fully-managed service for transforming and enriching data in stream (real time) and batch (historical) modes with equal reliability and expressiveness.
 
### Application Definition & Image Build
1. [Alibaba Cloud Serverless Workflow](https://www.alibabacloud.com/product/serverless-workflow) - Alibaba Cloud develops highly scalable cloud computing and data management services.
2. [Artifact Hub](https://github.com/artifacthub/hub) - Find, install and publish Kubernetes packages.
3. [Backstage](https://github.com/backstage/backstage) - An open platform for building developer portals.
4. [Bitnami](https://tanzu.vmware.com/application-catalog) - A customizable selection of open source software from the Bitnami collection that is continuously maintained and verifiably tested for use in production environments.
5. [Buildpacks](https://github.com/buildpacks/pack) - CLI for building apps using Cloud Native Buildpacks.
6. [Carvel](https://github.com/vmware-tanzu/carvel-ytt) - A set of reliable, single-purpose, composable tools that aid in your application building, configuration, and deployment to Kubernetes.
7. [Chef Habitat](https://github.com/habitat-sh/habitat) - Modern applications with built-in automation.
8. [CloudARK KubePlus](https://github.com/cloud-ark/kubeplus) - Build SaaS for your containerized applications.
9. [CodeZero](https://codezero.io/) - Tools for local collaborative development in pre-production Kubernetes clusters.
10. [DeployHub](https://www.deployhub.com/) - DeployHub makes it easy for IT Engineers to govern their microservice supply chain and deliver secure, high-quality microservices at scale.

⬆ [Back to Contents](#contents) ⬆


### Continuous Integration & Delivery
1. [Agola](https://github.com/agola-io/agola) - Open Source CI/CD platform with advanced features and architecture.
2. [Akuity](https://github.com/argoproj/argo-cd) - The Argo enterprise company modernizing the cloud-native toolchain with Argo, the industry-leading open-source suite of Kubernetes-native application delivery software.
3. [Appveyor](https://www.appveyor.com/) - Appveyor Systems Inc. aim is to give powerful continuous integration and deployment tools to every .NET developer.
4. [Argo](https://github.com/argoproj/argo-workflows) - Workflow engine for Kubernetes.
5. [AWS CodePipeline](https://aws.amazon.com/codepipeline/) - A fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates.
6. [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) - Continuously build, test, and deploy to any platform and cloud.
7. [Bamboo](https://www.atlassian.com/software/bamboo) - Bamboo Server is the choice of professional teams for continuous integration, deployment, and delivery.
8. [Brigade](https://github.com/brigadecore/brigade) - Event-driven scripting for Kubernetes.
9. [Buildkite](https://buildkite.com/) - A platform for running fast, secure, and scalable continuous integration pipelines on your own infrastructure.
10. [Bunnyshell](https://bunnyshell.com/) - An EaaS platform that enables fast, dead-simple environment creation and management for teams and developers who want to release better code faster.

⬆ [Back to Contents](#contents) ⬆


## Orchestration & Management
### Scheduling & Orchestration
1. [Amazon Elastic Container Service (ECS)](https://aws.amazon.com/ecs/) - A highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS.
2. [Apache Mesos](https://github.com/apache/mesos) - A cluster manager that provides efficient resource isolation and sharing across distributed applications, or frameworks.
3. [Azure Service Fabric](https://github.com/Microsoft/service-fabric) - A distributed systems platform for packaging, deploying, and managing stateless and stateful distributed applications and containers at large scale.
4. [Capsule](https://github.com/clastix/capsule) - Multi-tenancy and policy-based framework for Kubernetes.
5. [Clusternet](https://github.com/clusternet/clusternet) - Managing your Kubernetes clusters (including public, private, edge, etc) as easily as visiting the Internet.
6. [Clusterpedia](https://github.com/clusterpedia-io/clusterpedia) - Clusterpedia is used for complex resources search across multiple clusters, support simultaneous search of a single kind of resource or multiple kinds of resources existing in multiple clusters.
7. [Crossplane](https://github.com/crossplane/crossplane) - Cloud Native Control Planes.
8. [Docker Swarm](https://github.com/moby/swarmkit) - A toolkit for orchestrating distributed systems at any scale. It includes primitives for node discovery, raft-based consensus, task scheduling and more.
9. [Fluid](https://github.com/fluid-cloudnative/fluid) - An orchestration platform for elastic data abstraction and acceleration in cloud native environment.
10. [iSSCloud](https://www.isoftstone.com/htmlsen/Cloudnativeservices/20220613/6acf55b26d0c4625b2fb8ca54cee58ab.html) - iSoftStone Multi-cloud Management System is an enterprise-level cloud management platform applied in multiple public clouds and public-private hybrid cloud scenarios.

⬆ [Back to Contents](#contents) ⬆


### Coordination & Service Discovery
1. [Apache Zookeeper](https://github.com/apache/zookeeper) - A centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.
2. [AWS Cloud Map](https://aws.amazon.com/cloud-map/) - A cloud resource discovery service. 
3. [CoreDNS](https://github.com/coredns/coredns) - A DNS server that chains plugins.Cloud Native Storage
4. [etcd](https://github.com/etcd-io/etcd) - Distributed reliable key-value store for the most critical data of a distributed system.
5. [k8gb](https://github.com/k8gb-io/k8gb) - A cloud native Kubernetes Global Balancer.
6. [KubeBrain](https://github.com/kubewharf/kubebrain) - A High Performance Metadata System for Kubernetes.
7. [Nacos](https://github.com/alibaba/nacos) - An easy-to-use dynamic service discovery, configuration and service management platform for building cloud native applications.
8. [Netflix Eureka](https://github.com/Netflix/eureka) - AWS Service registry for resilient mid-tier load balancing and failover.

⬆ [Back to Contents](#contents) ⬆


### Remote Procedure Call
1. [Apache Thrift](https://github.com/apache/thrift) - A lightweight, language-independent software stack for point-to-point RPC implementation.
2. [Avro](https://github.com/apache/avro) - A data serialization system.
3. [CloudWeGo](https://github.com/cloudwego/kitex) - CloudWeGo is ByteDance's open source Golang-centric middleware that can be used to quickly build enterprise-class cloud native architectures.
4. [Dubbo](https://github.com/apache/dubbo) - A high-performance, java based, open source RPC framework.
5. [go-zero](https://github.com/zeromicro/go-zero) - A web and rpc framework written in Go. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
6. [gRPC](https://github.com/grpc/grpc) - The C based gRPC (C++, Python, Ruby, Objective-C, PHP, C#).
7. [kratos](https://github.com/go-kratos/kratos) - A microservice-oriented governance framework implements by golang, which offers convenient capabilities to help you quickly build a bulletproof application from scratch.
8. [SOFARPC](https://github.com/sofastack/sofa-rpc) - A high-performance, high-extensibility, production-level Java RPC framework.
9. [SRPC](https://github.com/sogou/srpc) - High performance, low latency, lightweight enterprise-level RPC system, which supports Baidu bRPC, Tencent tRPC, thrift protocols.
10. [TARS](https://github.com/tarsCloud/tars) - A high-performance RPC framework that provides an integrated solution of microservice governance.

⬆ [Back to Contents](#contents) ⬆


### Service Proxy
1. [Avi Networks](https://avinetworks.com/) - Avi Networks drives automation and intelligence across multi-cloud environments with intent-based application services, including LB and WAF.
2. [BFE](https://github.com/bfenetworks/bfe) - Open-source layer 7 load balancer derived from proprietary Baidu FrontEnd.
3. [Caddy](https://github.com/caddyserver/caddy) - A powerful, enterprise-ready, open source web server with automatic HTTPS written in Go.
4. [Citrix ADC (formerly NetScaler ADC)](https://www.citrix.com/products/citrix-adc/) - An application delivery and load balancing solution that provides a high-quality user experience for your web, traditional, and cloud-native applications regardless of where they are hosted.
5. [Contour](https://github.com/projectcontour/contour) - A Kubernetes ingress controller using Envoy proxy.
6. [Envoy](https://github.com/envoyproxy/envoy) - Cloud-native high-performance edge/middle/service proxy.
7. [F5](https://www.f5.com/) - F5 Networks provides application security and delivery tools.
8. [Gimbal](https://github.com/projectcontour/gimbal) - An ingress load balancing platform capable of routing traffic to multiple Kubernetes and OpenStack clusters. Built by Heptio in partnership with Actapio.
9. [HAProxy](https://github.com/haproxy/haproxy) - HAProxy Load Balancer's development branch (mirror of git.haproxy.org).
10. [Inlets](https://github.com/inlets/inlets-pro) - Secure HTTP and TCP tunnels that just work.

⬆ [Back to Contents](#contents) ⬆


### API Gateway
1. [3Scale](https://github.com/3scale/apicast) - 3scale API Gateway APIcast is an API gateway built on top of NGINX.
2. [Akana](https://www.akana.com/) - A full lifecycle API management platform that supports multicloud deployments with industry-leading security.
3. [APIOAK](https://github.com/apioak/apioak) - Full Lifecycle Management API Gateway.
4. [Azure API Management](https://github.com/azure/api-management) - A hybrid, multi-cloud API, full lifecycle management platform for APIs across all environments. It allows customers to self-host API gateways as containers on Kubernetes.
5. [Easegress](https://github.com/megaease/easegress) - A Cloud Native traffic orchestration system.
6. [Emissary-Ingress](https://github.com/emissary-ingress/emissary) - An open source Kubernetes-native API gateway for microservices built on the Envoy Proxy.
7. [EnRoute OneStep Ingress](https://github.com/saarasio/enroute) - Connectivity and Security for your Microservice at Kubernetes Ingress using one helm command. Built on Envoy Proxy.
8. [Gloo](https://github.com/solo-io/gloo) - The Feature-rich, Kubernetes-native, Next-Generation API Gateway Built on Envoy.
9. [Gravitee.io](https://github.com/gravitee-io/gravitee-api-management) - OpenSource API Management.
10. [Hango](https://github.com/hango-io/hango-gateway) - Hango API Gateway, build on Envoy & Istio.

⬆ [Back to Contents](#contents) ⬆


### Service Mesh
1. [Aeraki Mesh](https://github.com/aeraki-mesh/aeraki) - Aeraki Mesh allows you to manage any layer-7 traffic in a service mesh.
2. [AWS App Mesh](https://aws.amazon.com/app-mesh/) - A service mesh that provides application-level networking to make it easy for your services to communicate with each other across multiple types of compute infrastructure.
3. [Consul](https://github.com/hashicorp/consul) - A distributed, highly available, and data center aware solution to connect and configure applications across dynamic, distributed infrastructure.
4. [EaseMesh](https://github.com/megaease/easemesh) - A service mesh implementation for connecting, control, and observe services in spring-cloud.
5. [Glasnostic](https://glasnostic.com/) - Glasnostic makes modern cloud applications resilient by shaping how systems interact, automatically and in real-time.
6. [Gloo Mesh](https://github.com/solo-io/gloo-mesh) - The Service Mesh Orchestration Platform.
7. [greymatter.io](https://greymatter.io/) - greymatter.io uses the service mesh ecosystem to create connected intelligence and intervention for next-gen modern infrastructure.
8. [Istio](https://github.com/istio/istio) - Connect, secure, control, and observe services.
9. [Kuma](https://github.com/kumahq/kuma) - The multi-zone service mesh for containers, Kubernetes and VMs. Built with Envoy. CNCF Sandbox Project.
10. [Linkerd](https://github.com/linkerd/linkerd2) - Ultra light, ultra simple, ultra powerful. Linkerd adds security, observability, and reliability to Kubernetes, without the complexity.

⬆ [Back to Contents](#contents) ⬆


## Runtime
### Cloud Native Storage
1. [Alibaba Cloud File Storage](https://www.alibabacloud.com/product/nas) - Alibaba Cloud File Storage enables you to have a distributed file system with unlimited capacity and performance scaleing with a single namespace,high-performance, high reliability, high availabily and scalable file storage services.
2. [Alluxio](https://github.com/alluxio/alluxio) - Alluxio, data orchestration for analytics and machine learning in the cloud.
3. [Amazon Elastic Block Store (EBS)](https://aws.amazon.com/ebs/) - An easy to use, high performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction intensive workloads at any scale.
4. [Arrikto](https://www.arrikto.com/) - Democratizing Kubernetes Machine Learning with Kubeflow, simplified data automation, and accelerated collaboration.
5. [Azure Disk Storage](https://azure.microsoft.com/en-us/services/storage/disks/) - Get HDD/SSD durability, scalability, availability, and security you need for all your workloads—from mission-critical workloads to test scenarios.
6. [Carina](https://github.com/carina-io/carina) - An high performance and ops-free local storage for kubernetes.
7. [Ceph](https://github.com/ceph/ceph) - A distributed object, block, and file storage platform.
8. [CloudCasa by Catalogic Software](https://cloudcasa.io/) - Backup-as-a-service for Kubernetes and cloud native applications.
9. [Commvault](https://www.commvault.com/software-defined-storage) - Commvault provides a data and enterprise backup software.
10. [CubeFS](https://github.com/cubeFS/cubefs) - A cloud native distributed storage platform.

⬆ [Back to Contents](#contents) ⬆


### Container Runtime
1. [containerd](https://github.com/containerd/containerd) - An open and reliable container runtime.
2. [Firecracker](https://github.com/firecracker-microvm/firecracker) - Secure and fast microVMs for serverless computing.
3. [CRI-O](https://github.com/cri-o/cri-o) - Open Container Initiative-based implementation of Kubernetes Container Runtime Interface.
4. [gVisor](https://github.com/google/gvisor) - Application Kernel for Containers.
5. [Inclavare Containers](https://github.com/inclavare-containers/inclavare-containers) - A novel container runtime, aka confidential container, for cloud-native confidential computing and enclave runtime ecosystem.
6. [Kata Containers](https://github.com/kata-containers/runtime) - Kata Containers version 1.x runtime (for version 2.x see https://github.com/kata-containers/kata-containers).
7. [Lima](https://github.com/lima-vm/lima) - Linux virtual machines, typically on macOS, for running containerd.
8. [lxd](https://github.com/lxc/lxd) - Powerful system container and virtual machine manager.
9. [rkt](https://github.com/rkt/rkt) - A pod-native container engine for Linux. It is composable, secure, and built on standards.
10. [runc](https://github.com/opencontainers/runc) - CLI tool for spawning and running containers according to the OCI specification.

⬆ [Back to Contents](#contents) ⬆


### Cloud Native Network
1. [Antrea](https://github.com/antrea-io/antrea) - Kubernetes networking based on Open vSwitch.
2. [Aviatrix](https://www.aviatrix.com/) - A multi-cloud network platform that provides security and operational visibility.
3. [Cilium](https://github.com/cilium/cilium) - eBPF-based Networking, Security, and Observability.
4. [CNI-Genie](https://github.com/cni-genie/CNI-Genie) - CNI-Genie for choosing pod network of your choice during deployment time. Supported pod networks - Calico, Flannel, Romana, Weave.
5. [Cumulus](https://www.nvidia.com/en-us/networking/ethernet-switching) - A software company that designs and sells Linux operating systems for networking hardware.
6. [DANM](https://github.com/nokia/danm) - TelCo grade network management in a Kubernetes cluster.
7. [FabEdge](https://github.com/FabEdge/fabedge) - Secure Edge Networking Solution Based On Kubernetes.
8. [FD.io](https://github.com/FDio/vpp) - LF Networking is the center of gravity for global carrier and enterprise networking success.
9. [Flannel](https://github.com/flannel-io/flannel) - A network fabric for containers, designed for Kubernetes.
10. [Guardicore Centra](https://www.guardicore.com/cyber-security-platform) - Guardicore provides micro-segmentation and workload protection solutions for data centers and public clouds.

⬆ [Back to Contents](#contents) ⬆


## Provisioning
### Automation & Configuration
1. [Airship](https://github.com/airshipit/treasuremap) - Reference Airship manifests, CICD, and reference architecture.
2. [Akri](https://github.com/project-akri/akri) - A Kubernetes Resource Interface for the Edge.
3. [Ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform that makes your applications and systems easier to deploy and maintain.
4. [Apollo](https://github.com/apolloconfig/apollo) - A reliable open-source configuration management system.
5. [AWS CloudFormation](https://aws.amazon.com/cloudformation/) - AWS CloudFormation provides a common language for you to describe and provision all the infrastructure resources in your cloud environment.
6. [BOSH](https://github.com/cloudfoundry/bosh) - An open source tool chain for release engineering, deployment and lifecycle management of large scale distributed services.
7. [Cadence Workflow](https://github.com/uber/cadence) - A distributed, scalable, durable, and highly available fault-oblivious stateful code platform.
8. [CDK for Kubernetes (CDK8s)](https://github.com/cdk8s-team/cdk8s) - CDK8s lets you define Kubernetes apps and components using familiar programming languages and object-oriented APIs.
9. [Chef Infra](https://github.com/chef/chef) - A powerful automation platform that transforms infrastructure into code automating how infrastructure is configured, deployed and managed across any environment, at any scale.
10. [Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian) - Rules engine for cloud security, cost optimization, and governance, DSL in yaml for policies to query, filter, and take actions on resources.

⬆ [Back to Contents](#contents) ⬆


### Container Registry
1. [Alibaba Cloud Container Registry (ACR)](https://www.alibabacloud.com/zh/product/container-registry) - A cloud-native artifacts management platform that helps your team build, manage, and ship containerized applications, also provides vulnerability analysis, global synchronization, content trust, and more functionalities out of the box.
2. [Amazon Elastic Container Registry (ECR)](https://aws.amazon.com/ecr/) - A fully-managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images.
3. [Azure Registry](https://azure.microsoft.com/en-us/services/container-registry/) - Azure Container Registry allows you to store images for all types of container deployments including DC/OS, Docker Swarm, Kubernetes, and Azure services such as App Service, Batch, Service Fabric, and others.
4. [Distribution](https://github.com/distribution/distribution) - The toolkit to pack, ship, store, and deliver container content.
5. [Dragonfly](https://github.com/dragonflyoss/Dragonfly2) - An intelligent P2P based image and file distribution system, it also provides a variety of enterprise-level (efficiency, stability, safety, low-cost) product features.
6. [Google Container Registry](https://cloud.google.com/container-registry/) - A single place for your team to manage Docker images, perform vulnerability analysis, and decide who can access what with fine-grained access control.
7. [Harbor](https://github.com/goharbor/harbor) - An open source trusted cloud native registry project that stores, signs, and scans content.
8. [IBM Cloud Container Registry](https://www.ibm.com/cloud/container-registry) - Detect vulnerabilities before images are ever deployed to containers. Store and distribute Docker images in your managed private registry.
9. [JFrog Artifactory](https://jfrog.com/artifactory/) - Shipping updates continuously and automatically has become a critical element of any successful operation.
10. [Kraken](https://github.com/uber/kraken) - P2P Docker registry capable of distributing TBs of data in seconds.

⬆ [Back to Contents](#contents) ⬆


### Security & Compliance
1. [Airlock](https://www.airlock.com/) - Application security, API Security, Identity and Access Management, 2FA, Security for container environments.
2. [Alcide](https://www.alcide.io/) - Alcide provides dev-to-production security for workloads running in Kubernetes & Istio.
3. [Anchore](https://github.com/anchore/anchore-engine) - A service that analyzes docker images and scans for vulnerabilities.
4. [Apolicy](https://www.apolicy.io/) - Apolicy fuses security and compliance into your cloud native development pipeline. Using policy-as-code, we automate risk, policy and remediation from source to production.
5. [Aqua](https://www.aquasec.com/) - A software company providing cloud-native security technology.
6. [Armo](https://www.armosec.io/) - Embedding Visibility, Security and Control into every cloud workload and Empowering DevOps to Deploy Inherently Secure Workloads.
7. [Aserto](https://github.com/aserto-dev/runtime) - Fine-grained, policy-based, real-time authorization for APIs and microservices. Aserto is the maintainer of the Topaz and Open Policy Registry OSS projects.
8. [Black Duck](https://www.synopsys.com/software-integrity/security-testing/software-composition-analysis.html) - Black Duck provides a comprehensive software composition analysis (SCA) solution for managing security, quality, and license compliance risk that comes from the use of open source and third-party code in applications and containers.
9. [Bloombase](https://www.bloombase.com/) - Bloombase is the intelligent storage firewall company.
10. [Capsule8](https://capsule8.com/) - High-performance attack protection for Linux production environments – whether containerized, virtualized, or bare-metal, on-prem or cloud.

⬆ [Back to Contents](#contents) ⬆


### Key Management
1. [Athenz](https://github.com/AthenZ/athenz) - Open source platform for X.509 certificate based service authentication and fine grained access control in dynamic infrastructures.
2. [Authing](https://github.com/Authing/Authing) - IDaaS/IAM solution that can Auth to web and mobile applications.
3. [CyberArk Conjur](https://github.com/cyberark/conjur) - CyberArk Conjur automatically secures secrets used by privileged users and machine identities.
4. [Keycloak](https://github.com/keycloak/keycloak) - Open Source Identity and Access Management For Modern Applications and Services.
5. [OAuth2 Proxy](https://github.com/oauth2-proxy/oauth2-proxy) - A reverse proxy that provides authentication with Google, Azure, OpenID Connect and many more identity providers.
6. [ORY Hydra](https://github.com/ory/hydra) - OpenID Connect and OAuth Provider written in Go - cloud native, security-first, open source API security for your infrastructure. 
7. [Pinniped](https://github.com/vmware-tanzu/pinniped) - Pinniped is the easy, secure way to log in to your Kubernetes clusters.
8. [Pomerium](https://github.com/pomerium/pomerium) - An identity and context-aware access proxy.
9. [SPIFFE](https://github.com/spiffe/spiffe) - A framework and set of standards for identifying and securing communications between application services.
10. [Square Keywhiz](https://github.com/square/keywhiz) - A system for distributing and managing secrets.

⬆ [Back to Contents](#contents) ⬆



# kubernetes-contrail-day-one

## Chapter 1: Short chapter to lay the basic foundations 
Learning Objective 1: The reader will be able to explain basics Docker, container, Iptables and contrail 

### Topic 1: Using Docker and containers 
1.    Understanding containers, compare to VMs
2.    Understanding Docker
3.    Containers as part of VNs
4.    Linux cgroup, namespace, iptables
### Topic 2: contrail overview 
1.   Contrail Architecture Fundamentals 
2.   contrail controller & VRouter 

## Chapter 2: Short chapter to cover Kubernetes basics 
Learning Objective 1: The reader will be able to explain and build basics Kubernetes setup  

### Topic 1: Kubernetes Architecture  
1.    What is Kubernetes 
2.    Kubernetes master – Kube-apiserver , Kube-controller , Kuber-Scheduller and etcd
3.    Kubernetes node – kubelet , kube-proxy 
4.    Pod 
5.    Kubernetes networking  

### Topic 2: Building Kubernetes POD
1.   YAML file for Kubernetes 
2.   POD example using YAML files
3.   Kubectl tool 
4.   Login to container 
5.   Intra-POD communications  

## Chapter 3: Kubernetes advanced topics  
Learning Objective 1: The reader will be able to explain and build advanced Kubernetes features using YAML  

### Topic 1: Kubernetes features 
1.    Label, Label example 
2.    Services (Cluster IP , node port , load balancing) 
3.    Ingress 
4.    Replication Controller & Replica set
5.    Deployment
6.    POD health check & Readniess Probe  
7.    Volumes, storage 
8.    Scaling (manually , auto scaling) 
9.    ConfigMap 
10.  Affinity/ anti-affinity  
11. DNS

### Topic 2: Building Kubernetes 
1.   kubeadm , minikube ,…
2.   Helm charts  

## Chapter 4: Kubernetes and Contrail integration 
Learning Objective 1: The reader will be able to explain different Kubernetes/contrail implementations
Learning Objective 2: The reader will be able to build applications using Kubernetes and contrail     

### Topic 1: Contrail with Kubernetes implementations 
1.    Kubernetes/Contrail Architecture  
2.    Kubernetes and contrail installation options   
3.    Nested installation on OpenStack  
4.    OpenShift overview 


### Topic 2: Kubernetes integration with Contrail 
1. Kubernetes to contrail object mapping
2. namespaces and isolation
3. Services 
4. ingress 
5. Kubernetes Network Policy with Contrail Security
6. IP-fabric-source NAT
7. visualization


### Topic 3: building multitenant websites example   
1. Building 2 websites using Kubernetes POD
2. Using Contrail to offer networking and security services 

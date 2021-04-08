# DevOpsModelProject

**Architectural diagram**

![alt text](https://user-images.githubusercontent.com/64398490/114076727-a1c53500-98c4-11eb-9d82-ef4e9e7fb387.png?raw=true)





**High level folder hirarchy**

```
├── Website
│   ├── Dockerfile
│   ├── main.go
│   └── mywebsite
├── ansible
│   └── site.yaml
├── jenkinsfile
└── kubernetes
    └── deploymemt.yaml
```

** Traffic Flow **

ELB (loadbalancer) --> kubernetest service --> pods --> container 

```
 _   ________    _     
| | / /|  ___|  | |    
| |/ / | |_ __ _| |__  
|    \ |  _/ _` | '_ \ 
| |\  \| || (_| | |_) |
\_| \_/\_| \__,_|_.__/ 
                       

```

# Goals

The fabrics projects goal is to simplify creating and managing applications in Kubernetes.

It attempts to solve the following issues

- Reduce complexity
- Security out of the box
- Create common deployments 
- Provide a complete out of the box experience (Batteries included)
- Automation of common operational tasks
- Without introducing new frameworks

# What is a fabric

A fabric is a declarative way of deploying common fully operationalized stacks  such as:

- MEAN
- MEVN
- MERN
- LAMP
- Ruby
- Flutter
- Go
- Web3
- Spark
- Delta Lake


# How are fabrics built

Fabrics are created using the defacto package manager for Kubernetes HELM.  Creating fabrics with help requires a level of standardization in creating helm charts.  To solve this problem we introduce two concepts:

- std-helm: Standardizes creating manifest for Kubernetes resources types.  Today, debugging/understanding helm charts is a time consuming task
- structured-helm: Normalizes values.yaml variables allowing them to drive helm chart generated manifest across multiple projects

# Magic Carpet (mcarp)

Is a AI driven set of Kubernetes operators that automate day-to-day management.

Magic carpet is only possible because of fabrics as they significantly reduce the complexity caused by snowflake deployments.






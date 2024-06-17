# DevOps

FSWD

## DevOps

#### Dev => Development Team

#### Ops => Operation Team

#### Devops and CICD (Docker & Kubernetes)

#### Dev -------------------------------------------------------------> Ops

#### write code + share code -----------------------------------------> Testing + Scaling, Bug Fixing

#### Developer Team -> Operation Team -> Testing Team

#### complexity of appln more => den time to build the appln will be more

### Scenario:

#### Team of 3 members => Book My Show Appln >> All have diff OS (Mac, Windows, Linux)

    Person-1                Person-2                Person-3
    (windows)                (Mac)                    (Linux)
    Packages

#### It works on my m/c

#### Book My Show Appln (Resources): RAM: 4GB ROM: 1TB GPU: 2GB

## Virtualisation

(I could be able to run virtual OS on my local OS) Local OS in case of Person -2 => Mac Virtualisation Virtual OS => Windos

### Basic Arch:

#### Windows (RAM, ROM, GPU) || Virtual OS

#### OS || Local OS

### Adv Arch:

#### Windows Virtual OS Unix Virtual OS

#### 7Gb, 500GB, 1GB 3GB, 500GB, 1GB

#### || Internal Resource Sharing

#### Base/Local OS

#### 8GB, 1TB, 2GB

## Containersation (Docker)

#### Base: Windows Virtual OS (2Gb, 250Gb) Unix Virtualisation OS (2GB, 250GB)

#### Docker Engine (4GB, 500Gb)

#### Base Local OS (8GB, 1TB)

#### Book My Show Appln (3GB)

#### Windows Virtual OS (2Gb, 250Gb) Unix Virtualisation OS (2GB, 250GB)

#### Docker Engine (4GB, 500Gb)

#### Base Local OS (8GB, 1TB)

## Docker >> EC2 Instance >> Img and Container

## Kubernetes (Orchestra)

## Nodes

#### >> Master Node (A person holding stick in Orchestra event | Lead)

#### >> Child Node (A group of people who will be following the lead guidance)

## NGINX (Light Weight Servers)

## AWS >> EC2 (Virtual Machines) Amazon Elastic Compute Cloud Service

## Docker

#### >> Image

#### >> Containers

#### Image(Parent) Containers(Child) || Server

## Client Server Architecture

## Kubernetes

#### >> Docker Deamon ---> Server (Initialization)

#### >> Docker Client ---> Client

#### >> Docker Swarm --> Orchestra (Master | Main Node | Configuration)

> > Master Node
> > Child Node
> > POD (Container)
> > Development (Wher it will keep close eye on Pod)
> > Example: I want to run a server in the docker with 3 container on my book my show clone applns

Docker >> Image >> Cont 1 >> Cont 2 >> Cont 3

Kubernetes >> Masster Node

> > Child Node | POD -1 >> Child Node | POD -2 >> Child Node | POD -3

Master Node Child Node -1 Child Node -2 Child Node -3 Development

Development: Analayze and manatin all the PODs/Child Nodes/ Servers/ Containers

Docker > Kubernetes

AWS >> Service: EC2 (VM) => Unix OS Base OS >> Windows

Client
Kuberntes
Server
Serv1 (1000req/hr) => 200-300 similar reqs Proxy Serv1

Client sends req -> Proxy Serv -> Serv1

Client sends req -> Proxy Serv for Proxy Serv-> Proxy Serv -> Serv1

NGINX (Light Weight Server) >> Reverse Proxy >> Load Balancing

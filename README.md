# HumanGov Application

Plataforma voltada para cidadania digital, transformação digital e inovação tecnológica.

## Objetivo

O HumanGov Application tem como objetivo desenvolver uma solução tecnológica que aproxime cidadãos, instituições e serviços públicos através de recursos digitais modernos.

## Tecnologias Planejadas

- Python
- Inteligência Artificial
- Cloud Computing
- AWS
- GitHub

## Funcionalidades Planejadas

- Cadastro de usuários
- Assistente com Inteligência Artificial
- Portal de serviços
- Painel administrativo
- Integração com APIs

## Roadmap

- [x] Criação do repositório
- [ ] Definição da arquitetura
- [ ] Desenvolvimento do backend
- [ ] Desenvolvimento do frontend
- [ ] Integração com IA
- [ ] Implantação em nuvem

## Arquitetura Proposta

```text
Usuário
    │
    ▼
Frontend Web
    │
    ▼
Backend API
    │
    ├── Banco de Dados
    │
    ├── Inteligência Artificial
    │
    └── Serviços em Nuvem

Kubernetes Deployment (Amazon EKS)
Além da implementação utilizando Amazon ECS, a aplicação HumanGov também foi implantada em um cluster Kubernetes utilizando Amazon Elastic Kubernetes Service (EKS).

🚀 Tecnologias Utilizadas
Amazon EKS
Kubernetes
Docker
Amazon ECR
AWS Load Balancer Controller
Application Load Balancer (ALB)
Kubernetes Ingress
Amazon S3
Amazon DynamoDB
IAM Roles for Service Accounts (IRSA)
OIDC Provider
Helm
kubectl
eksctl
✅ Funcionalidades Implementadas
Deploy da aplicação HumanGov em Kubernetes
Publicação de imagens no Amazon ECR
Configuração do AWS Load Balancer Controller
Integração com Amazon S3
Integração com Amazon DynamoDB
Exposição da aplicação através de Ingress e Application Load Balancer
Gerenciamento de permissões utilizando IAM e OIDC
Arquitetura Cloud Native baseada em containers
📖 Artigo Técnico
Leia o artigo completo:

(https://medium.com/@eduardoscarvalho/deploy-de-uma-aplica%C3%A7%C3%A3o-saas-na-aws-com-kubernetes-eks-docker-amazon-ecr-alb-s3-e-dynamodb-27d88d4022ee)

🌐 Principais Aprendizados
Kubernetes na AWS
Administração de Clusters EKS
Deploy de aplicações containerizadas
Ingress e Application Load Balancer
IAM Roles e OIDC
Integração com serviços gerenciados da AWS
Troubleshooting de ambientes Kubernetes
Arquitetura Cloud Native



## Status

🚧 Em desenvolvimento

## Autor

Eduardo Silva Carvalho

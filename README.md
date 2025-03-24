# Projeto DevOps

## Sobre o projeto
- Este projeto foi desenvolvido com o intuito de práticar e estudar DevOps, nele eu desenvolvo um site de vendas (Dev) e faço deploy no ambiente de produção (Ops) utilizando as principais ferramentas e conceitos DevOps atualmente.

## Tecnologias
- Docker
- Kubernete
- DigitalOcean
- Prometheus
- Grafana
- Pipeline CI/CD (GitHub actions)

## Objetivos do projeto
- Implementar um ciclo completo de DevOps, desde o desenvolvimento até o monitoramento.
- Automatizar o processo de integração e entrega contínua (CI/CD).
- Criar um ambiente escalável, resiliente e monitorado em tempo real.

## Arquitetura
-Aplicação containerizada utilizando Docker.
-Orquestração dos containers com Kubernetes (K8s).
-Deploy realizado em cluster Kubernetes na DigitalOcean.
-Separação de ambientes (dev, staging, produção).

## Pipeline CI/CD
- Integração contínua configurada via GitHub Actions.
- Build e push da imagem Docker para o Docker Hub.
- Deploy contínuo no cluster Kubernetes.
- Deploy contínuo do Prometheus & Grafana.

## Monitoramento
- Prometheus configurado para coleta de métricas da aplicação e infraestrutura.
- Grafana para dashboards e alertas em tempo real.

## Boas práticas DevOps aplicadas
Infraestrutura como código (IaC) com manifests Kubernetes (YAML).
Uso de secrets e config maps para variáveis sensíveis.
Observabilidade com logs, métricas e alertas.
Deploy azul/verde ou rolling updates no Kubernetes.

## Resultados
- Redução do tempo de deploy com automação.
- Maior confiabilidade e previsibilidade nas entregas.
-Facilidade de escalar a aplicação conforme a demanda.


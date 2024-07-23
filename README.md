# ud-microservices-springboot-helm

Used with ud-microservices-springboot repo; Repo with Helm related updates [branch:helm]

- branch: helm; deployed all services and microservices in K8s cluster via helm charts; tried debugging issue with tempo ingester going crashloopbackoff;
- branch: helm; implemented Grafana service in K8s via bitnami template, modified values.yaml; configured datasources in grafana values.yaml
- branch: helm; implemented Loki and Tempo service in K8s via bitnami template, modified values.yaml
- branch: helm; implemented Prometheus service in K8s via bitnami template, modified values.yaml
- branch: helm; implemented Kafka service in K8s via bitnami template, modified values.yaml
- branch: helm; implemented Keycloak service in K8s via bitnami template, modified values.yaml
- branch: helm; configured environment-specific helm chart to deploy all microservices; dev, qa, prod
- branch: helm; configured helm charts for other microservices: loans, card, configserver, eurekaserver, gatewayserver, message
- branch: helm; configured accounts microservice helm charts; values.yaml, cart.yaml; linked to dependencies
- created helm chart /template common across jayslabs microservices: service, deployment, configmap
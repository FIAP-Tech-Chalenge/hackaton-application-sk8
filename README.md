# hackaton-application-k8s

## Como rodar o projeto

Fazer a conexão com a AWS e rodar o comando abaixo para criar a infraestrutura:

```bash
terraform init
terraform plan
terraform apply
```

Para rodar o projeto com o Kubernetes, basta executar os comandos abaixo:

Entrar na pasta k8s e rodar o comando abaixo:
```bash
kubectl apply -k .
```

Para finalizar a execução do Kubernetes, basta rodar o comando abaixo:

```bash
kubectl delete -k .
```
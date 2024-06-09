# Projeto-conclusao curso k8s - Fabricio Bernardo de Oliveira
 Projeto de conclusão do curso de k8s
Nome : Fabricio Bernardo de Oliveira - Taking
Command Livelo 


# Projeto final curso de Kubernetes
A ideia Principal é criar um Namespace , chamado fb-prd , onde existe o Deployment fabricio, com 3 replicas , Apesar de ter assistido as aulas confesso que tenho dificuldades com o mundo do desenvolvimento porque não é de fato minha area de atuação/ conhecimento , então tive muitas dificuldades para entregar o projeto, no entanto os comandos de teste de cada tarefa do projeto final estão rodando corretamente , só nao consegui de gato testar o service , pois não carrega a imagem. 

# versão do minikube 
minikube version: v1.33.1
commit: 5883c09216182566a63dff4c326a6fc9ed2982ff

# versão do Docker
Client: Docker Engine - Community
 Version:           26.1.4
 API version:       1.45
 Go version:        go1.21.11
 Git commit:        5650f9b
 Built:             Wed Jun  5 11:29:19 2024
 OS/Arch:           linux/amd64
 Context:           default

 #Ambiente Wsl Ubuntu  Rodando em Windows 11 


#Etapas do Projeto

 1 Deployment - fabricio;
 1 Service - fabricio
 1 Namespace - Fb-prd 
 1 Configmap - cm-fb
 1 Secret - user-pwd



*o service foi criado apartir do comando "kubectl expose deployment fabricio"  por isso não gerou arquivo yaml- mas foi evidenciado seu funcionamento

# Alguns  Comandos Utilizados para realização de testes 

-Kubectl get pods -n fb-prd -o wide
-Kubectl get nodes
-Kubectl get services 
-Kubectl get namespaces
-Kubectl get secrets
-Kubectl get cm-cm-fb
-Kubectl Describe configmap 
-kubectl get pods -A | grep f
-Kubectl describe service
-kubectl get pods -n fb-prd -o wide
-kubectl  describe secret

# Alguns Comandos utilizados para criar o projeto 

-kubectl apply -f pod.yaml
-kubectl delete deployment fabricio
-kubectl apply -f secret.yaml
-kubectl create secret generic user-pwd --from-literal=username=fbadmin --from-literal=password=fbhb@2609
-ubectl expose deployment fabricio

*** Obs: Arquivo Word mostrando cada etapa do projeto anexado ao repositorio 
 

 

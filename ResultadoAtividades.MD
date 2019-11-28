# Agile-Devops - Resultado as atividades da avaliação final


## Nome da Equipe
[jupiter]

## Integrantes
 - I1 - Nildo Wilpert Jr
 - I2 - Jean Motta
 - I3 - Guilherme Mauricio Pires
 - I4 - Bruno De Castro

## Atividade 01
- Repositório DockerHUB:  brunocri2/jupiter

## Atividade 02
- Nome do Chart: jupiter
- Repositorio GIT: brunocri2/agile-devops-avaliacao

##Atividade 03
- Comando usado para adicionar o repo do museum no helm: helm repo add chartmuseum http://senaicharts.agile-devops.club
- Comando usando para realizar o deployment da aplicação: helm install --name jupiter --tiller-namespace=kube-system jupiter && kubectl port-forward jupiter 8081:6080 
- Endereço completo para acessar a aplicação: http://localhost:8081/vnc.html

## Atividade 04
Listagem dos problemas encontrados e resolvidos:

- gateway rodando em namespace diferente do virtual service, mas dentro do yaml está declarando apenas o nome do gateway sem a namespace.
- B
- C
- D

Snapshot dos pods Running: [nome do arquivo de imagem]


## Atividade 05
- Nome do JOB: JUPITER

## Atividade 06:
Cole o resultado do planejamento:
var.server_port
  The port the server will use for HTTP requests

  Enter a value: 8080

Refreshing Terraform state in-memory prior to plan...
The refreshed state will be used to calculate this plan, but will not be
persisted to local or remote state storage.


------------------------------------------------------------------------

Error: Error running plan: 1 error(s) occurred:

* provider.aws: No valid credential sources found for AWS Provider.
	Please see https://terraform.io/docs/providers/aws/index.html for more information on
	providing credentials for the AWS Provider

## Atividade 07:
Qual o contéudo do arquivo:

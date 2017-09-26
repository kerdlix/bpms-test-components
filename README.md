# Testes de componentes do Red Hat BPM Suite

## Documentos
Necessário configurar: 
* Marshelling Strategy
* Remoteable classes
* Anexar variável do tipo: org.jbpm.document.Document
* Documentação: [https://access.redhat.com/solutions/2567701](https://access.redhat.com/solutions/2567701)

## Envio de email
Exemplo utiliza tarefa de Email e Notificação.
Necessario configurar:
* Email Work Item Handler no deployment descriptor
* Necessario iniciar o servidor FakeSMTP como sudo
* Documentação: [https://access.redhat.com/solutions/1440913](https://access.redhat.com/solutions/1440913)

## Escalonamento
Necessario configurar:
* Reassignment na tarefa manual

## Tarefas humanas
Necessario configurar:
* Formulários

## Regras
Necessario configurar:
* Data Object para entrada e saída de valores

## Webservice REST
Necessario configurar:
* Parâmetros da tarefa REST
* Instalação do WebService que será chamado. Neste caso é necessário a instalação de: [https://github.com/kerdlix/ws-rest-random-value](https://github.com/kerdlix/ws-rest-random-value)


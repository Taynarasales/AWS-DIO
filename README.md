

# Gerenciando Instâncias EC2 na AWS

## Descrição

Este laboratório teve como objetivo praticar o gerenciamento de instâncias EC2 na AWS, compreendendo conceitos essenciais como criação de imagens AMI, snapshots EBS e administração de servidores virtuais na nuvem.

## Objetivos

* Entender o funcionamento do Amazon EC2.
* Criar e gerenciar instâncias.
* Aprender sobre imagens AMI.
* Utilizar snapshots EBS para backup.
* Documentar os processos realizados.



## O que é o Amazon EC2?

O Amazon Elastic Compute Cloud (EC2) é um serviço da AWS que permite criar e gerenciar servidores virtuais na nuvem. Com ele, é possível executar aplicações sem a necessidade de manter infraestrutura física.

### Principais Benefícios

* Escalabilidade.
* Alta disponibilidade.
* Pagamento sob demanda.
* Diversos sistemas operacionais disponíveis.



## Criação de uma Instância EC2

### Etapas realizadas

1. Acesso ao Console AWS.
2. Navegação até o serviço EC2.
3. Seleção da opção "Launch Instance".
4. Escolha da imagem do sistema operacional.
5. Configuração do tipo da instância.
6. Criação ou seleção de Key Pair.
7. Configuração do Security Group.
8. Inicialização da instância.

### Resultado

Instância criada e executada com sucesso.



## AMI (Amazon Machine Image)

As imagens AMI são modelos utilizados para criar novas instâncias EC2.

### Vantagens

* Padronização de ambientes.
* Implantação rápida.
* Reutilização de configurações.

### Processo realizado

1. Seleção da instância existente.
2. Criação de uma AMI personalizada.
3. Validação da imagem criada.

---

## Snapshots EBS

Os Snapshots EBS permitem criar cópias de segurança dos volumes anexados às instâncias.

### Benefícios

* Backup dos dados.
* Recuperação rápida.
* Migração entre regiões.

### Processo realizado

1. Acesso ao volume EBS.
2. Criação do Snapshot.
3. Verificação do status de conclusão.

---

## Aprendizados Obtidos

Durante o laboratório foi possível compreender:

* Como funciona o serviço EC2.
* A importância das imagens AMI.
* O uso de Snapshots para backup.
* Conceitos de segurança utilizando Security Groups.
* Boas práticas de gerenciamento de recursos na AWS.

---

## Conclusão

Este laboratório permitiu consolidar conhecimentos fundamentais sobre computação em nuvem utilizando AWS. O gerenciamento de instâncias EC2, a criação de AMIs e a utilização de Snapshots EBS são habilidades essenciais para profissionais que atuam com infraestrutura e serviços em nuvem.

## Referências

* Documentação Oficial AWS EC2
* Documentação AWS EBS
* Formação AWS da DIO

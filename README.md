# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 11 de agosto de 2025

**Empresa:** Abstergo Industries

**Responsável:** Breno Augusto de Castro Pereira

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Breno Augusto. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto foi dividido em 3 etapas fundamentais para a operação da empresa:

Etapa 1: Armazenamento Inteligente de Arquivos

* **Nome da ferramenta:** Amazon S3
  
* **Foco da ferramenta:** Guardar todos os tipos de arquivos de forma segura e econômica.
  
* **Descrição de caso de uso:** Usaremos o Amazon S3 para armazenar catálogos de produtos, notas fiscais, pedidos de compra e outros documentos. A função _Intelligent-Tiering_ irá, de forma automática, reduzir o custo de armazenamento de arquivos que não são acessados com frequência, gerando economia sem nenhum esforço manual.
  

Etapa 2: Servidor Principal da Aplicação

* **Nome da ferramenta:** Amazon EC2
  
* **Foco da ferramenta:** Fornecer a capacidade de computação para rodar o sistema da empresa.
  
* **Descrição de caso de uso:** O Amazon EC2 funcionará como o "servidor na nuvem" onde nosso sistema principal (o portal dos parceiros de venda) será executado.Vai permitir aumentar ou diminuir a potência do servidor conforme a necessidade, garantindo que o sistema esteja sempre disponível para os nossos parceiros.
  

Etapa 3: Comunicação Segura com Parceiros

* **Nome da ferramenta:** Amazon API Gateway
  
* **Foco da ferramenta:** Criar um ponto de entrada seguro e controlado para a comunicação entre sistemas.
  
* **Descrição de caso de uso:** O API Gateway será a entreda para que os sistemas das empresas parceiras possam se comunicar com o nosso. Através dele, um parceiro poderá consultar nosso estoque ou enviar um novo pedido de forma segura e padronizada, facilitando a integração e garantindo que apenas parceiros autorizados tenham acesso.
  

Conclusão

A implemetação de ferramentas na empresa Abstergo Industries, segurança para os dados, flexibilidade para o crescimento e um controle de custos otimizado, que aumentará a eficiencia e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

* Diagrama de arquitetura da solução AWS
  
* Planilha de custos comparativos antes e depois da implementação
  
* Logs de execução das instâncias EC2
  
* Políticas de acesso ao S3 e ao API Gateway
  
* Manual de configuração das ferramentas utilizadas
  

*Assinatura do Responsável pelo Projeto:*

###### Breno Augusto de Castro Pereira

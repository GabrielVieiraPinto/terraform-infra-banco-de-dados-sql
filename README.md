# terraform-infra-banco-de-dados-sql
subida de recurso de banco de dados sql  na azure usando terraform
# Provisão de Recursos na Microsoft Azure com Terraform

Este repositório contém scripts Terraform para provisionar recursos na plataforma Microsoft Azure. O Terraform é uma ferramenta de código aberto que permite criar, alterar e gerenciar infraestrutura como código (IaC) de maneira eficiente e repetível.

## Conteúdo do Repositório

- **/azure-resources**: Este diretório contém os scripts Terraform para criar recursos na Azure.
- **/modules**: Diretório opcional que pode conter módulos reutilizáveis para provisionar recursos comuns na Azure.
- **main.tf**: O arquivo principal que define os recursos a serem provisionados.
- **variables.tf**: Arquivo de definição de variáveis que podem ser personalizadas para diferentes ambientes.
- **terraform.tfvars**: Arquivo de variáveis que podem ser configuradas com valores específicos para o ambiente.
- **README.md**: Este arquivo.

## Pré-requisitos

Antes de começar, você precisará do seguinte:

- [Terraform](https://www.terraform.io/) instalado em seu ambiente.
- Uma conta da Microsoft Azure.
- Autenticação configurada para a Azure (por exemplo, arquivo de autenticação de serviço ou variáveis de ambiente).

## Como Usar

1. Clone este repositório em seu ambiente local.

2. Personalize as variáveis no arquivo `terraform.tfvars` de acordo com suas necessidades.

3. Navegue até o diretório `/azure-resources`.

4. Inicialize o projeto Terraform:

   ```bash
   terraform init


# Desafio: Automação de Infraestrutura com Script

## 📌 Descrição

Este projeto tem como objetivo automatizar a criação da infraestrutura básica de um sistema Linux utilizando um script Shell. O script realiza automaticamente as seguintes tarefas:

- Criação de usuários
- Criação de grupos de usuários
- Criação de diretórios
- Definição de permissões apropriadas para cada diretório

Com isso, sempre que uma nova máquina virtual for iniciada, será possível executar este script e ter todo o ambiente pronto para uso, sem a necessidade de configurações manuais.

## 🚀 Objetivo

Facilitar e padronizar a configuração inicial de ambientes Linux, promovendo agilidade e eficiência no processo de provisionamento de máquinas.

## 📂 Estrutura do Projeto

- `infrastructure-setup.sh`: Script principal responsável por toda a criação e configuração da infraestrutura.
- `README.md`: Documento com informações sobre o projeto.

## 🛠️ Funcionalidades do Script

- Criação de grupos (ex: `GRP_ADM`, `GRP_VEN`, `GRP_SEC`)
- Criação de usuários e associação aos grupos correspondentes
- Criação de diretórios públicos e privados
- Aplicação de permissões e propriedade dos diretórios

## 🖥️ Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

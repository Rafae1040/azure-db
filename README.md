# 📄 Configuração de Instância de Banco de Dados no Microsoft Azure

Este repositório documenta a experiência prática de configuração de uma instância de Banco de Dados SQL no Microsoft Azure, como parte de um laboratório de aprendizagem.

## 🎯 Objetivo

Criar e configurar uma instância de banco de dados SQL no Azure.

Documentar o processo técnico passo a passo.

Consolidar dicas e aprendizados para futuras implementações.

Utilizar o GitHub como ferramenta de documentação e compartilhamento de conhecimento técnico.

## 🧪 Objetivos de Aprendizagem

✅ Aplicar os conceitos aprendidos em um ambiente prático
✅ Documentar processos técnicos de forma clara e estruturada
✅ Utilizar o GitHub para versionamento e compartilhamento de conhecimento

## 📝 Conteúdo do Repositório

Arquivo

Descrição

README.md

Explicação geral do projeto

notas/criacao-instancia.md

Passo a passo da criação da instância SQL

notas/configuracoes-seguranca.md

Configuração de firewall, regras de acesso e autenticação

notas/dicas-gerais.md

Dicas úteis sobre custo, desempenho e manutenção

imagens/

Prints ilustrativos da criação e configuração

docs/arquitetura.png

(Opcional) Diagrama ilustrando a arquitetura do serviço

## ⚙️ Etapas do Laboratório

1. Criar Instância SQL no Azure

Acesse o Portal do Azure

Selecione "Criar um recurso" > Banco de Dados > Banco de Dados SQL

Defina:

Nome do banco

Nome do servidor (ou crie um novo)

Região

Método de autenticação

📷 Veja prints na pasta imagens/

2. Configurar Acesso e Segurança

Configure o firewall para permitir IPs confiáveis

Defina regras de acesso via Azure Active Directory (opcional)

Teste a conexão com ferramentas como Azure Data Studio ou DBeaver

3. Monitoramento e Manutenção

Ative métricas de desempenho no painel da instância

Use recursos como escalonamento automático e backup geo-redundante

Documente boas práticas de manutenção

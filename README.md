# 🔨 Sistema de Gerenciamento - Casa de Leilões

Este repositório contém a implementação inicial do sistema de controle de inventário e vendas para uma casa de leilões, focado na organização e transparência do processo de lances.

## 📝 Descrição do Projeto
O projeto foi desenvolvido para automatizar a rotina de leiloeiros, permitindo o cadastro de produtos e o monitoramento em tempo real do status de cada item. O sistema garante que cada produto passe pelas etapas de "A Venda" até a confirmação como "Vendido", mantendo o histórico de valores atualizado.

## 🛠️ Tecnologias e Ferramentas
* **Linguagem Principal:** Java ☕
* **Persistência de Dados:** MySQL / MariaDB 🐬
* **Versionamento:** Git & GitHub 🚀
* **Interface de Banco:** phpMyAdmin

## 📊 Estrutura de Dados
O sistema opera sobre o banco de dados `uc11`, utilizando a tabela `produtos` com a seguinte configuração:
* **ID:** Identificador único (Auto-incremento).
* **Nome:** Descrição do item leiloado.
* **Valor:** Preço base ou de arremate.
* **Status:** Situação atual do lote.

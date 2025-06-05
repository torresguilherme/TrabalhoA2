# 🎁 Sistema de Cadastro de Doações – Painel Interativo (Colab)

Este projeto é um painel interativo desenvolvido com Python no Google Colab, criado para gerenciar o fluxo de doações de alimentos, ONGs e estoques. Ele foi desenvolvido como parte de um trabalho acadêmico por um grupo de estudantes, utilizando tecnologias simples e acessíveis.

## 👥 Grupo Quinta-feira (Cadastro de Doações)

- Guilherme José Silva Torres – 38141264  
- Cauã da Costa Cordeiro – 38446880  
- Pedro Henrique Pontes – 39294072  
- Arthur Moreira do Vale – 38634384  
- Johnatan Antunes – 39333086  
- Andre Felipe Oliveira – 38536935  

---

## 💻 O que é o sistema?

Um sistema interativo que permite:

- ✅ Cadastrar alimentos com controle de validade e estoque  
- ✅ Cadastrar ONGs com dados de contato  
- ✅ Registrar doações associando alimentos, quantidades, doadores e ONGs  
- ✅ Visualizar relatórios com status de vencimento e alertas de estoque  
- ✅ Exportar relatórios completos para Excel  

---

## 🧩 Tecnologias utilizadas

- **Python** – Linguagem principal do projeto  
- **SQLite** – Banco de dados leve e embutido  
- **pandas** – Manipulação de dados e exportação para Excel  
- **ipywidgets** – Interface interativa no Jupyter/Colab  
- **Google Colab** – Ambiente de execução online e gratuito  

---

## 🗂️ Funcionalidades principais

### 🔹 1. Cadastro de Alimentos
- Nome, quantidade, unidade (kg, g, L, etc.) e validade
- Ao cadastrar, o alimento entra no banco e aparece nas opções de doação

### 🔹 2. Cadastro de ONGs
- Nome e contato
- ONGs aparecem nas opções de destino da doação

### 🔹 3. Registro de Doações
- Seleção do doador, alimento, quantidade e ONG
- O sistema verifica o estoque antes de registrar
- Estoque é atualizado automaticamente

### 🔹 4. Listagens Inteligentes
- Alimentos com status visual:
  - ✅ OK
  - ⚠️ Próximo do vencimento ou estoque baixo
  - ❌ Vencido
- Listagem completa de ONGs e doações

### 🔹 5. Exportação de Relatórios
- Exporta 3 arquivos `.xlsx`:
  - `relatorio_alimentos.xlsx`
  - `relatorio_ongs.xlsx`
  - `relatorio_doacoes.xlsx`

---

## 📸 Exemplo da Interface

> Executado diretamente no Google Colab usando `ipywidgets` para interação:

https://imgur.com/a/cEcQrJW  

LINK DO Google Colab: https://colab.research.google.com/drive/1vKdyEvgUR2pfmV9d5dztSQJK0SwvK5te?usp=sharing






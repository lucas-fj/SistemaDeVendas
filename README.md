#Sistema de vendas em Java
Sistema simples de gerenciamento de vendas e estoque desenvolvido em Java, executado via console.

O projeto simula o funcionamento de uma pequena loja, permitindo registrar vendas, controlar estoque, visualizar relatórios e identificar a maior compra realizada.

#Funcionalidades
- Registro de vendas com múltiplos produtos
- Controle de estoque
- Reposição de produtos
- Histórico de vendas
- Identificação da maior venda realizada
- Listagem de produtos disponíveis

#Produtos disponíveis
- Calça
- Camisa
- Bermuda
- Saia
- Blusa
- Moletom
- Meia
- Tênis
- Bota
Cada produto possui: Quantidade em estoque, preço fixo e controle de vendas

#Regras de Negócio
- Não é possível vender mais do que o estoque disponível
- O usuário deve confirmar a compra antes de finalizar
- O estoque é atualizado automaticamente após cada venda
- O sistema armazena:
  - Total vendido por produto
  - Valor total de cada compra
  - Cliente que fez a maior compra

#Funcionalidades do Menu
1 - Registrar Venda 
2 - Repor Estoque 
3 - Mostrar Estoque 
4 - Histórico de Vendas 
5 - Maior Venda 
6 - Integrantes (Integrantes que participaram do desenvolvimento do trabalho) 
7 - Sair

#Controle de Estoque
- O estoque inicial já vem definido no sistema
- Pode ser atualizado manualmente pela opção Repor Estoque
- O sistema impede vendas com quantidade indisponível

#Como executar 
1. Clone o repositório:
    git clone https://github.com/lucas-fj/trabalhoGrauA
2. Compile o arquivo:
    javac trabalhoGrauA.java
3. Execute o programa:
    java trabalhoGrauA

#Objetivo do Projeto
Esse projeto foi desenvolvido como um trabalho acadêmico com o objetivo de de praticar lógica de programação, manipulação de variáveis,
estruturas de decisão, estruturas de repetição e demais conceitos de programação.

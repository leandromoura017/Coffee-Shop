# Coffee Shop


##  Estrutura do Projeto 
O website tem três páginas principais:


### 1. Página Inicial (Index) 
- Lista de cafés é obtidas via uma requisição GET para a API local. 
- Cada item da lista exibi: 
  - Título. 
  - Descrição. 
  - Preço. 
  - Imagem. 
  - Ingredientes. 
  - Botão para adicionar o café ao carrinho. 
- Um ícone de carrinho de compras no cabeçalho que: 
  - Mostra o número atual de itens no carrinho. 
  - E quando clica, leva para a página de carrinho de compras. 
  - Adiciona um item ao web storage.

#### Imagem:
![Image](https://github.com/user-attachments/assets/712caa14-c764-4284-8fa3-4b5aca68b35b)
    
### 2. Página de Carrinho de Compras 
- Lista todos os itens adicionados ao carrinho (web storage). 
- Cada item da lista exibi: 
  - Nome do café. 
  - Preço. 
  - Quantidade. 
- Funcionalidades: 
  - Botões para adicionar e remover unidades de cada item. 
  - Exibição do total acumulado do carrinho. 
  - Um botão "Finalizar Compra" que redireciona para a página de 
finalização.

#### Imagem:
![Image](https://github.com/user-attachments/assets/6bae3580-4073-4026-9fb5-71c7c1ac1810)

### 3. Página de Finalização de Compra 
- Exibe os itens que estavam no carrinho no momento de sua finalização. 
- Inclui um formulário com os seguintes campos: 
  - Endereço de entrega. 
  - Seleção de método de pagamento (cartão de crédito, boleto e PIX). 
- Um botão "Finalizar" que: 
  - Valida se os campos estão preenchidos de maneira adequada. 
  - Exibe uma mensagem de confirmação da compra. 
  - Limpa os dados do carrinho no Web Storage.

  #### Imagem:
![Image](https://github.com/user-attachments/assets/1fdfa48b-3212-4af6-86ae-5e490ae438b6)

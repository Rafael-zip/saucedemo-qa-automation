 # Observações - sauceDemo

 ## standard_user	
 - login: efetuado com sucesso redirecionando para a pagina 
 - Comportamento geral: Funcionou corretamente as funções apresentadas no site,menu hamburguer está com todas funcionalidades corretas e funcionais, 
imagem e preço dos produtos está certo ao adicionar produtos contabiliza corretamente no carrinho e ao efetuar o pagamento ele responde com a mensagem "Thank you for your order!" simbolizando compra efetuada com sucesso 

 ## locked_out_user
 - login: Após clicar para efetuar o login aparece a mensagem "Epic sadface: Sorry, this user has been locked out."  identificando que o usuário está bloqueado
 - comportamento geral: Mensagem de erro e a página se mantem a mesma

 ## problem_user
 -login: Ao efetuar o login e ser redirecionado de página
 a imagem dos produtos mudam para a foto de um cachorro e ficam todas iguais
 -comportamento geral: imagens dos produtos estão erradas 
e ao clicar no endereço "sobre" ele responde com um erro 404 "Página nao encontrada" 

 ## performance_glitch_user
 -O que ficou lento: Quando uma opção e selecionada ele leva mais tempo para carregar a página 

 ## error_user
 -Onde deu erro: ao tentar efetuar o pagamento dos produtos a página fica branca e perde todos os elementos dela 

 ## visual_user
 -Diferenças visuais notadas: as imagens tem tamanhos diferentes, os textos estão sem formatação, 
valor dos produtos está errado o ìcone do carrinho de compras esta fora de posição e o menu hamburguer esta torto


--- Requisitos Funcionais ---

## RF001
O sistema deve permitir o login com usuário e senha válidos, redirecionando para a página de produtos.

## RF002
O sistema deve impedir o login de usuários bloqueados, exibindo a mensagem "Epic sadface: Sorry, this user has been locked out."

## RF003
O usuário deve conseguir adicionar produtos ao carrinho, com a quantidade sendo contabilizada corretamente no ícone do carrinho.

## RF004
O sistema deve permitir a finalização da compra, exibindo a mensagem "Thank you for your order!" ao final do processo.

## RF005
O menu lateral (hambúrguer) deve exibir suas opções corretamente e todas devem ser funcionais. 

## RF006
As imagens devem estar de acordo com o produto oferecido.

## RF007
Os preços necessitam estar alinhados aos produtos corretos.

## RF008
O sistema deve ter a capacidade de remover itens do carrinho  

## RF009
As opções de redirecionamento para as redes sociais do site devem ser funcionais.

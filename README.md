# Rocketstore - versão web

O projeto é parte do conteúdo do bootcamp GoStack - turma 9 da Rocketeseat.

Para entendimento dos conceitos de Redux - Saga, foi desenvolvido sistema simples de carrinho de compras, onde o usuário adicionar os produtos ao carrinho, tem um feedback no botão do produto de quantos itens do mesmo está no carrinho e também um feedback de quantos itens distintos tem no carrinho.

Ao acessar o carrinho, o usuário pode alterar a quantidade de produtos e também remover um produto da lista. Existe ainda um controle com relação ao estoque, impedindo que o usuário acrescente uma quantidade de itens superior ao estoque do mesmo.

No projeto, pode-se destacar algumas libs utilizadas para chegar ao resultado esperado

 - Json-server: simula uma API a partir de um arquivo .json onde se pode ter acesso a diversas rotas e até mesmo relacionamento entre o dados. Ideal para projetos no qual o backend ainda não está pronto para adiantar a escrita do código do frontend. Neste projeto, o arquivo utilizado para esse fim é o server.json;
 - Toastify: Lib para notificações. Neste projeto foi utilizo para notificar estoque insuficiente do produto;
 - Immer: Manipulação de dados do state no redux. Sabe-se que o states no redux são imutáveis, porém essa lib facilita e muito o trabalho. Possibilita trabalhar os dados dos states "modificando-os", porém sem ferir os princípios da imutabilidade;
 - History: Permite a navegação dentro do Saga. A lib aguarda a execução do Saga para depois redirecionar o usuário para a rota destino;
 - Reactotron: Utilizado principalmente para acompanhar os disparos dos actions do redux e saga. Ótimo para monitorar como os dados estão sendo gerados e armazenados nos states;

## Instação e execução

 1. List item

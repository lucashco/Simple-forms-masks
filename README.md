# Simple-forms-masks
Uma forma simples de adicionar mascaras nos campos de seu formulário!

## Começando
Adicione um atributo chamado data-simplemask em seu campo de input.
```
<input type="text" data-simplemask="cpf" />
```

## Valores aceitos
O atributo data-simplemask atualmente recebe 4 valores, sendo eles: 

| Valor      | Descrição |
| ------     | --------- |
| cpf        | Cria mascara para CPF |
| cnpj       | Cria mascara para CNPJ |
| telefone   | Cria mascara para Telefone fixo ou móvel |
| cep        | Cria mascara para Cep |

Caso queira checar, no arquivo main.js existe um objeto chamado "masks" que possuí todas funções de mascaras.

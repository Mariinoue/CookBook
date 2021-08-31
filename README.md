# CookBook 👩‍🍳 👨‍🍳
Projeto de API para pessoas que gostam de organizar suas receitas. 


Arquitetura MVC 
Server 
App.js 
Utils.js
Routes
Models
Controllers

Banco de dados NoSQL 
- receitas.json 

```
{
 "id":
 "title":"string",
 "fonte":https://www.panelinha.com.br/blog/alimentacaosaudavel/Quarto-round-file-de-peixe-congelado-x-file-de-peixe-empanado-congelado,
 "foto": img,
 "ingredientes":["strings"],
 "modo de fazer": "strings",
 "avaliação":number,
 "observações":"strings"
 }
```

- Rota GET mostrar todas as receitas ('receitas/todos') getAll
- Rota GET filtar pelo título da receita('receitas/título) getByTitle
- rota Get filtrar pelo id da receita ('receitas/:id) getById

-Rota POST criar novas receitas pelo usuario ('novaReceita')createRecipe
registrar se contiver pelo menos titulo e ingredientes

- Rota DELETE deletar receitas pelo id ('receitas/:id/delete) deleteRecipe

- Rota PUT alterar alguma informação da receita ('receitas/:id/update) updateRecipe 

-------------------------------------------
Próximas rotas

buscar pelo alimento 
criar uma lista de compras 

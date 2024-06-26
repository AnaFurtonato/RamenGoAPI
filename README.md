
# RamenGo API

API para uma aplicação web chamada RamenGo, uma plataforma onde o usuário possa montar um pedido de ramen, escolhendo os tipos de caldos e proteínas do prato.

A API contém endpoints que fornecerão as opções disponíveis de caldos e proteínas.

Esses endpoints retornam dados que serão utilizados para popular listas de seleção para o usuário, no qual o mesmo poderá selecionar apenas uma opção de cada lista para montar o seu pedido.

Além dos endpoints de listagem, tem também um endpoint que permitirá ao usuário fazer um pedido. Este endpoint recebe as seleções do usuário e processa o pedido, retornando uma confirmação com um código do pedido.





## Stack utilizada

**Backend:** C# e ASP.NET Core


## Funcionalidades

- Listar Caldos, lista todos os caldos disponíveis:

Endpoint: 
```bash
 GET /api/broths
```

- Listar Proteínas, lista todas as proteínas disponíveis

Endpoint: 
```bash
 GET /api/proteins
```

- Fazer Pedido, permite ao usuário fazer um pedido.

Endpoint: 
```bash
 POST /api/orders
```


## Retorno da API pelo Swagger

Return of the Broths:

![retornoApiBroths](https://github.com/AnaFurtonato/RamenGoAPI/assets/79214802/f7d1d88a-8e57-4ed3-9219-663e0d622676)

Return of Proteins:

![retornoApiProteins](https://github.com/AnaFurtonato/RamenGoAPI/assets/79214802/c7c52f38-b344-4abd-8f94-b0c0fa358107)

Order Returns:

![retornoApiOrders](https://github.com/AnaFurtonato/RamenGoAPI/assets/79214802/dc63d4d9-7262-4342-b89b-7e449272dcf2)




## Instalação

Antes de iniciar o projeto em sua maquina, é importante ter o ambiente de desenvolvimento configurado corretamente. Certifique-se de ter o .NET 8.0 instalado em sua máquina. Link para download: https://dotnet.microsoft.com/pt-br/download

Clone o repositório do projeto do GitHub:

```bash
 git clone https://github.com/AnaFurtonato/RamenGoAPI.git
```
    
## Autores

- [@AnaFurtonato](https://github.com/AnaFurtonato)


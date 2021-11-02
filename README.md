# estrelas_ecommerce
exercicio lead e produto https://dontpad.herokuapp.com/Lead
Exercício Ordinário - Lead Collector
Faça um API REST para cadastra possiveis leads de um sistema e ecommerce. 


A requisição para cadastrar um novo lead na lista deve serguir o seguinte padrão. 


URL da requisição: localhost:8080/leads
verbo do HTTP: POST
CORPO da REQUISIÇÃO: 
{      
    "email":"vinicius@xablau.com",     
     "nome":"Viny",      
    "telefone":"(11) 9961876755",      
    "produtos":[
        {            
            "nomeProduto":"Arroz",            
            "valor": 100.00      
        }
    ]
}


Resposta: 
Status HTTP 201
NÃO PRECISA DE CORPO


REGRAS DE NEGOCIO:
1 - Não pode cadastrar leads com o mesmo email e produto. 
2 - Caso um lead seja cadastro com um novo produto a lista de produtos do lead deve ser atualizada. 

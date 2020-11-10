# Teste de Automação para QA - CI&T

O objetivo deste repositório é disponibilizar o desafio visando atuar como QA na CI&T.

## Ferramentas utilizadas


## Cenários de teste
Foi utilizado o site https://opentdb.com/ para realizar os testes

### Cenário 1

**Funcionalidade:** Busca no Banco de Questões<br>
**Cenário:** Busca por questão inexistente<br>
**Dado** que navego para a página de busca do banco de questões<br>
**E** digito 'Science: Computers' no campo de busca<br>
**Quando** clico no botão de buscar<br>
**Então** visualizo uma mensagem de erro com o texto 'No questions found.'<br>

Foi automatizado em:


### Cenário 2

**Funcionalidade:** Busca no Banco de Questões<br>
**Cenário:** Busca por **categoria** existente<br>
**Dado** que navego para a página de busca do banco de **categorias**<br>
**E** digito 'Science: Computers' no campo de busca<br>
**Quando** clico no botão de buscar<br>
**Então** visualizo uma lista com 25 questões da categoria 'Science: Computers'<br>
**E** visualizo o controle de paginação<br>

Foi automatizado em: 


### Terceira parte

**Funcionalidade:** Ordenar lista de questões<br>
**Cenário:** Ordernação crescente da lista de questões por id<br>
**Dado** que navego para a página de [lista de questões](https://opentdb.com/browse.php) <br>
**Quando** clico no ícone de ordenar de forma crescente<br>
**Então** visualizo a lista de questões ordenadas de forma crescente<br>

Foi automatizado em: 

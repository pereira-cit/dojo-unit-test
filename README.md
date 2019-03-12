# O problema dos números Romanos

Numerais romanos foram criados na Roma Antiga e eles foram utilizados em todo o seu império. 

A numeração romana utiliza sete letras maiúsculas, que correspondem aos seguintes valores:

| Letras | Valores
|--------|---------
| I	     |   1
| V	     |   5
| X	     |   10
| L	     |   50
| C	     |   100
| D	     |   500
| M	     |   1000

Para representar outros números, os romanos combinavam estes símbolos, começando do algarismo de maior valor e seguindo a regra:

- Algarismos de menor ou igual valor à direita são somados ao algarismo de maior valor.
- Algarismos de menor valor à esquerda são subtraídos do algarismo de maior valor.

Por exemplo, XV representa 15 ( 10 + 5) e o número XXVIII representa 28. Há ainda uma outra regra: 

- Nenhum símbolo pode ser repetido lado a lado por mais de 3 vezes. Por exemplo o número 4 é representado pelo símbolo IV ( 5 - 1) e não por IIII.

ps: Existem outras regras (especialmente para número maiores) mas em linhas gerais, este é o problema a ser resolvido.

Dado um arquivo csv com uma coluna de números Romanos, converter para numerais arabicos e salvar no banco de dados em uma tabela DE-PARA. Exemplo:

| id | numeroRomano | numeroArabico
|----|--------------|--------------
|  1 | V            | 5
|  2 | VI           | 6
|  3 | VII          | 7
|  4 | VIII         | 8   
# infra-trabalho-1
Trabalho 1 da disciplina Infraestrutura de T. da Informação 

## Aplicação para o trabalho
Essa API backend foi utilizada por mim para estudos. Decidi aproveita-lá e usa-lá em um container no docker.
É uma livraria com endpoints de criação de livros, autores, categorias e afins. Informações são armazenadas no banco em memória h2. É em java utilizando springboot.

## Executando a aplicação
Para executar a aplicação pode ser feito de duas maneiras: Abrir o projeto em uma IDE, baixar as dependencias, e rodar a aplicação com o spring boot. Após isso,
para visualizar os endpoints melhor, é possivel utilizar o swagger e cadastrar livros, categorias, autores, com comandos POST. E visualiza-los com endpoints GET.

A outra maneira é: gerar um executavél, rodar esse executavel java, e realizar por meio do post-man, por exemplo, as requisições GET e POST da API.

Todos os retornos da API são em formato JSON.
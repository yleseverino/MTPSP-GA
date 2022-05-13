# Projeto de réplica de algoritmo genético implementado pelo [Al-Furhudand Hussain](https://www.researchgate.net/publication/343350213_Genetic_Algorithms_for_the_Multiple_Travelling_Salesman_Problem) na linguagem de programação Julia

Para baixar o artigo basta clicar <a href="https://github.com/yleseverino/MTPSP-GA/raw/main/Artigo.pdf">aqui</a>


## Getting Started

Para rodar o algoritmo primeiramente é necessário instalar os seguintes pacotes:

- JLD
- StatsBase

Depois basta rodar executar o arquivo main.jl, nele está definido o número de caixeiros que será utilizado no teste e o número de vezes que o teste será executado, dentro do main.jl tb está definido as variáveis genéticas como taxa de mutação e cruzamento, número de gerações e o tamanho da população

Já caso queria mudar a instância de teste, como por exemplo utilizar  MTSP-51, basta entrar no arquivo GraphYle.jl e alterar a variavel de load da matrix
>Para gerar essas variaveis foi utilizado o arquivo `get_distance_matrix.py` com os dados da TSPLIB



## Authors

* **Yle Severino Carvalho** - *Autor* 
* **Elder Vicente de Paulo Sobrinho** - *Orientador* 


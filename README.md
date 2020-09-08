# Airline Routes

**Número da Lista**: 1<br>
**Conteúdo da Disciplina**: Grafos 1<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 16/0133505  |  Lucas Gomes Silva |
| 19/0134623  |  Marcos Diego da Silva Gomes |

## Sobre 
O projeto tem como objetivo utilizar o conceito de grafos no ambiente de viagens aéreas para definir as opções de vôos, dado um aeroporto de origem e de destino. Utilizando a busca em largura (BFS) é demonstrado ao usuário as opções de aeroportos pelos quais passar para alcançar o aeroporto de destino.

## Screenshots
#### Grafo completo
![complete_graph](image/complete_graph.png)
#### Árvore de nós visitados pelo BFS
![traversal_tree](image/traversal_tree.png)
#### Caminho percorrido do nó inicial ao nó final
![path](image/path.png)

## Instalação 
**Linguagem**: Python<br>
É necessário ter instalado o **Python** o **pip** na máquina para executar o projeto.

1. Instale as bibliotecas necessário. (É recomendado utilizar um ambiente virtual para instalar e executar o projeto) <br>
    ``` pip install -r requirements.txt ```

## Uso 
### Para executar o projeto
Após estar dentro da pasta do projeto e com todas as bibliotecas instaladas, existe os seguintes passos para visualização do projeto: <br>
1. Execute o comando para abrir o jupyter-notebook:
    ``` jupyter notebook ```
2. Com a aba do jupyter aberta no navegador, abra o arquivo **AirlineRoutes.ipynb**
3. Na aba superior tem um menu chamado "Cell". Clicando nele, vai ter a opção "Run All", onde executará todas as células do arquivo.
4. Na célula 16 é possível alterar a origem e destino do voo.
5. Na célula 12 e 18 é possível descomentar a linha e visualizar a Lista de Adjacências e a Árvore resultante da BFS, respectivamente.

## Outros 
Dados de viagens aéreas coletados pela Agência Nacional de Aviação Civil (ANAC) e é utilizado voos das empresas LATAM e AZUL.





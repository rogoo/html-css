# Grid Responsive
Exemplo usando grid para criar uma lista de itens a ser exibidos, de forma responsiva.

Parte importantes é o **grid-template-columns**. 
```
grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
```
O ***auto-fit*** permite que os componentes se adequem ao espaço existente. A função ***minmax*** permite expecificar o mínimo e o máximo do tamanho de cada componente. No nosso caso, tamanho mínimo é 300px, então se tiver espaço de 600px, serão exibidos dois, se aumentar para 700px ou 800px, os dois itens vão se expandir usando a medida da fração (1fr), assim não deixando espaço vazio na tela. comforme aumenta o espaço, assim que chegar em 900px, serão exibidos três compomentes, e assim vamos que vamos.

Isso ai. Até.
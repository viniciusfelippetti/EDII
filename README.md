# Repositório para a matéria ALGORITMOS E ESTRUTURAS DE DADOS II

Aluno: Vinicius de Andrade Felippetti 

# Resumo
Essa tarefa teve o intuito de resolver 2 problemas envolvendo árvores BST e analisar sua complexidade. O primeiro problema é a busca pelo valor mais próximo de um valor escolhido. O segundo problema é achar o kº maior valor, com o k definido inicialmente.

<h3 align="left">Linguagem/Tecnologia Utilizada:</h3>
<p align="left"> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

# Explicação Problema 1 (ClosestValue)
Nesse problema, inicia-se setando o closestvalue sendo o valor da raiz da arvore. após isso, o target (valor passado como referência para a busca) é analisado, caso seja menor que o valor do nó atual, a navegação na árvore é feita pela esquerda, caso contrário, navega-se pela direita. Toda vez, que vai para um novo nó, é verificado se o valor absoluto da diferença entre o closestvalue e o target é menor que o valor absoluto da diferença do valor do nó atual e o target, caso essa verificação seja falsa, o valor do closestvalue é atualizado para o valor do nó atual. No final, teremoso return do closestvalue.

# Explicação Problema 2 (kThLargest)
Nesse problema, inicia-se navegando ao valor mais a direita da arvóre, toda vez que não há mais nó a direita, o contador cont é acrescentado 1 e comparado ao valor k passado na chamada da função, quando cont = k, o valor do nó atual é salvo na variável value e retornado no final da função. após isso, é chamado o nó a esquerda do nó atual e é verificado se existe um nó. Sendo assim, ele navega até o valor mais a direita da BST, e analisa a árvore inversamente.

# Tarefa 3
Link do vídeo com a explicação da tarefa 3: 
https://www.loom.com/share/dafeac358e824aa6a6ce3a05ca57ff3b?sid=79cb2b36-072d-49b7-b70c-2d129d2b90ac

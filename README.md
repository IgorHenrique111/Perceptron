Variação da taxa de aprendizado e épocas
Alterar a taxa de aprendizado (tamanho do passo na atualização dos pesos) e o número de epochs (quantas vezes o algoritmo percorre todo o conjunto de dados) impacta diretamente o treino. Com taxa 1.0 e 500 épocas, o perceptron treina rápido e leve.

Teste com a porta AND
Para testar, use entradas da porta AND e saídas [0, 0, 0, 1].

Função degrau
Foi criada a função ativacao_funcao e usada no predict. A sigmoide é mais suave e dá respostas “incertas”, enquanto a degrau é direta: ou ativa, ou não.

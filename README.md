# ESTRUTURA-DE-DADOS---Unidade-3
Para implementar o projeto conforme as especificações fornecidas, utilizei estruturas de dados como listas, pilhas e filas.

Análise da Ordem dos Números na Fila
Vamos analisar o que acontece em cada passo:

Lista inicial: [1, 2, 3, 4, 5]
Remover da lista e inserir na pilha:
A lista é uma estrutura FIFO (First In, First Out).
A pilha é uma estrutura LIFO (Last In, First Out), então os elementos são invertidos ao serem inseridos na pilha.
Resultado na pilha após inserir: [5, 4, 3, 2, 1]
Remover da pilha e inserir na fila:
Ao remover da pilha, os elementos saem em ordem inversa e são inseridos na fila.
A fila é uma estrutura FIFO, então os elementos são armazenados na ordem em que foram retirados da pilha.
Resultado na fila após inserir: [1, 2, 3, 4, 5]
Inserir novos números na lista: [6, 7, 8, 9, 10]
Repetir remoção da lista para pilha e da pilha para a fila:
A pilha novamente inverte a ordem dos elementos: [10, 9, 8, 7, 6]
Ao remover da pilha e inserir na fila: [6, 7, 8, 9, 10]
Resultado final na fila após todas as operações: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Justificativa para a Ordem dos Números
A ordem dos números exibidos na fila final está na mesma sequência em que foram inicialmente inseridos. Isso ocorre porque:

A primeira operação de remoção da lista para a pilha inverteu a ordem dos primeiros 5 números.
A remoção subsequente da pilha para a fila restaurou a ordem original desses números.
A segunda operação de remoção da lista para a pilha inverteu a ordem dos próximos 5 números.
A remoção subsequente da pilha para a fila restaurou a ordem original desses números.
Portanto, a fila final contém os números na mesma sequência em que foram originalmente inseridos.

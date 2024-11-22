Descrição do Projeto:
Este projeto simula a propagação de uma doença infecciosa em uma população fixa de 1000 pessoas ao longo de 30 dias, com uma probabilidade de infecção pré-definida. O objetivo é analisar como a infecção se propaga com o tempo e calcular a probabilidade de mais de 50% da população ser infectada ao final do período de simulação.

Funcionalidades:
Simulação da Propagação de Doença:

A simulação começa com um número inicial de indivíduos infectados e, a cada dia, novos infectados são calculados com base em uma probabilidade de infecção.
O número de infectados é limitado pela população total.
Parâmetros da Simulação:

populacao_total: Tamanho da população (1000 pessoas no exemplo).
infectados_iniciais: Número inicial de pessoas infectadas (1 no exemplo).
dias: Número de dias que a simulação cobre (30 dias no exemplo).
prob_infeccao: Probabilidade de uma pessoa infectada infectar outra.
num_simulacoes: Número de simulações independentes para obter uma média de resultados.
Probabilidade de Infecção Generalizada:

O código calcula a probabilidade de mais de 50% da população ser infectada ao final da simulação.
Visualização:

O projeto gera um gráfico com o número de infectados ao longo dos dias para 10 das simulações executadas. O gráfico mostra o comportamento da propagação da doença.

Tecnologias Utilizadas:
NumPy: Para cálculos e manipulação de arrays.
Matplotlib: Para visualização dos dados, criando gráficos que ilustram o número de infectados ao longo do tempo.


Como o Código Funciona:
Simulação da Doença:

O número de infectados começa com um valor inicial e, a cada dia, novos infectados são calculados com base na probabilidade de infecção. A função simular_propagacao repete esse processo para o número de dias especificado.
Cada simulação é executada várias vezes (1000 no exemplo), e o resultado de cada simulação é armazenado.
Cálculo da Probabilidade de Infecção Generalizada:

Após todas as simulações, a probabilidade de mais de 50% da população ser infectada ao final do período de simulação é calculada.
Visualização Gráfica:

Um gráfico é gerado usando Matplotlib, mostrando a evolução dos infectados em cada simulação ao longo dos dias. O gráfico ilustra as variações de propagação em diferentes simulações.

Resultados Esperados:
A simulação retornará uma estimativa da probabilidade de que mais de 50% da população seja infectada em 30 dias, com base no número de simulações executadas.
O gráfico gerado visualiza a propagação da infecção ao longo do tempo para múltiplas simulações, permitindo uma análise visual do comportamento da epidemia.

Exemplo de Saída:

Probabilidade de mais de 50% da população ser infectada: 84.30%

![image](https://github.com/user-attachments/assets/47ea4c90-0be0-4128-8731-8f0eff082732)





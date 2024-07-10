# Estudo de caso: Prevendo custos para abrir uma franquia
## Projeto usando regressão Linear para predição do custo anual de abertura de uma franquia

### Problematização:
A partir da taxa anual, é possível  prever qual será o custo inicial para montar a franquia?

A partir da taxa anual que já é conhecida, precisamos saber se é possível prever qual vai
ser o custo inicial para montar a franquia para começar o negócio.

Então, por exemplo, na aplicação informamos o custo anual da franquia de 100.000 e o
usuário clica no botão, ele vai dizer o investimento inicial será de 80.000.

Isso, claro, aproximado a qualquer aplicação de análise preditiva.

Ele dá um resultado do ponto de vista de estimativa.

### Solução:
Vamos utilizar a biblioteca Scikit Learn, dessa biblioteca vamos usar um método chamado de Regressão Linear.
Com esta técnica podemos fazer previsões de novos dados, que é o que o usuário vai informar na aplicação.

Carregamos os dados fornecidos, podemos ver os dados, geramos o gráfico de dispersão com a linha de melhor ajuste para o usuário entender como os dados estão distribuídos e como eles se relacionam.

No formulário vamos ter um controle onde o usuário insere o valor, O valor da franquia anual será processado após o clique no botão de processar e a aplicação vai mostrar o custo inicial do investimento inicial estimado.

### Tecnologias
- Python
- Streamlit
- Pandas
- Scikit-Learn
- Matplotlib
# Cardápio

---

### Descrição do Projeto:

O projeto consiste na análise do cardápio semanal dos restaurantes comunitários do Distrito Federal (DF) durante o mês de maio de 2024, utilizando a biblioteca `pandas` da linguagem Python para manipulação e tratamento de dados. A ideia foi explorar a diversidade de pratos oferecidos diariamente e seus valores calóricos, criando um DataFrame com as informações coletadas diretamente do site do Governo do Distrito Federal.

### Etapas do Desenvolvimento:

1. **Criação do Dicionário**: Foi criado um dicionário chamado `Cardapio`, onde cada chave representa uma categoria (como "Data", "Valor calórico (Kcal)", "Prato proteico", entre outros), e seus valores contêm os dados do cardápio de cada dia da semana.

2. **Transformação em DataFrame**: O dicionário foi convertido para um `DataFrame` utilizando o método `pd.DataFrame()`, permitindo manipular as informações como uma tabela, o que facilita o acesso e análise dos dados.

3. **Análises e Manipulações**:
   - **Exibição de Dados**: Usando métodos como `.head()` e `.iloc` para mostrar partes específicas ou o total de registros.
   - **Verificação de Dimensão**: O método `.shape` foi usado para identificar o número de linhas e colunas no DataFrame.
   - **Exclusão e Inclusão de Linhas**: Linhas foram removidas com o método `.drop()` e adicionadas utilizando `pd.concat()`.
   - **Transposição de Dados**: A estrutura do DataFrame foi invertida usando `.transpose()`, transformando linhas em colunas e vice-versa.
   - **Seleção Específica de Colunas**: Selecionando somente as colunas desejadas para análise.

4. **Fontes e Coleta de Dados**: Os dados foram coletados a partir do cardápio semanal disponibilizado no site oficial do Governo do Distrito Federal.
   - https://www.google.com/url?q=https%3A%2F%2Fwww.sedes.df.gov.br%2Fcardapio-dos-restaurantes-comunitarios%2F

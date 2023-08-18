## Modelo de Predição da Evolução de Pacientes com Covid-19 em Alagoas
O repositório contém o código e análise para a construção de um modelo que visa prever a evolução de pacientes acometidos pela Covid-19 no estado de Alagoas. O modelo é desenvolvido com base na linguagem R e abrange tanto a manipulação e visualização de dados quanto a construção de modelos de aprendizado de máquina.

### Bibliotecas
- tidyverse;
- janitor;
- lubridate;
- skimr;
- ggplot2;
- tidymodels.


### Bases de Dados
A base de dados utilizadas no projeto está no diretório data. 

### Pré-Processamento
Inicialmente, é realizada a etapa de leitura e preparação dos dados, onde os nomes das colunas são renomeados para um melhor compreensão. São tratados dados ausentes e colunas redundantes.

### Caracterização dos Dados
São realizadas análises descritivas para caracterizar os dados, como a quantificação de casos por data de atendimento, idade e sexo do paciente, município de residência, comorbidades e situação. Além disso, é elaborado um boxplot que relaciona as idades com as diferentes situações dos pacientes.

### Criação do Modelo de Predição
O objetivo é construir um modelo de predição utilizando a Random Forest. O workflow de modelagem é criado, hiperparâmetros são ajustados e o modelo final é treinado.


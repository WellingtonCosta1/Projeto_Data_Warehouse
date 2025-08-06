# Projeto_Data_Warehouse
Projeto de modelagem estrela com tabelas dimensionais e fato para análise de dados educacionais.


### Este projeto demonstra a construção de um Data Warehouse simples com SQLAlchemy e PostgreSQL, utilizando o modelo dimensional estrela para armazenar dados de desempenho de estudantes.

## 📌 Objetivo

Criar uma estrutura de banco de dados analítica (Data Warehouse) com foco em desempenho escolar, aplicando o conceito de modelagem dimensional (modelo estrela).

## 🧱 Estrutura do Modelo

O modelo contém as seguintes tabelas:

- **DimAluno**: informações do aluno (sexo, idade, endereço, etc.)
- **DimInfoPais**: informações dos pais (educação e profissão)
- **DimEscola**: dados da escola e apoios recebidos
- **DimTempo**: tempo de viagem, estudo e tempo livre
- **DimSaudeComportamento**: hábitos de saúde e comportamento dos alunos
- **FatoDesempenhoAluno**: tabela fato que armazena reprovações, faltas e notas

## ⚙️ Tecnologias Utilizadas

- Python 3.x
- SQLAlchemy
- PostgreSQL
- Pandas (opcional, para leitura dos dados)
- VS Code ou Jupyter Notebook

## 🧪 Como Executar

1. Certifique-se de ter o PostgreSQL rodando e um banco de dados chamado `escola`.
2. Crie um schema chamado `dw_escola`.
3. Instale os pacotes necessários:
   ```bash
   pip install sqlalchemy psycopg2 pandas



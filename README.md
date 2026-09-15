# Pipeline de Dados - Análise Nutricional
📊 **Projeto de Engenharia de Dados** para extrair, transformar e carregar dados nutricionais em um banco de dados PostgreSQL.

## 📌 Sobre o Projeto
Este projeto implementa um **ETL (Extract, Transform, Load)** que:
1. **Extrai** dados nutricionais de uma fonte.
2. **Transforma** os dados, calculando estatísticas como calorias diárias e consumo médio.
3. **Carrega** os dados no PostgreSQL.

## 🚀 Tecnologias Utilizadas
- 🐍 **Python** (Pandas, SQLAlchemy, Psycopg2)
- 🗄️ **PostgreSQL**
- 🐧 **Linux (WSL Ubuntu)**

## 📂 Arquitetura do Projeto
pipeline-dados/ 
│── src/ 
    ├── extract.py # Extração dos dados │ 
    ├── transform.py # Transformação dos dados │ 
    ├── load.py # Carregamento no PostgreSQL │ 
    ├── main.py # Orquestração do ETL 
│── requirements.txt # Dependências do projeto 
│── README.md # Documentação


## 🛠️ Configuração e Execução
### 1️⃣ Instalar Dependências
```bash
pip install -r requirements.txt


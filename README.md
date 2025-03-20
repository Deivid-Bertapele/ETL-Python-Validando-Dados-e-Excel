
Este projeto é projetado para validar e analisar dados de campanhas publicitárias usando Python. Inclui um módulo de validação de dados e um dashboard para visualizar indicadores-chave de desempenho (KPIs).

## Estrutura do Projeto

- `src/`: Contém o código-fonte para validação de dados.
  - `validador.py`: Define o modelo de dados e a lógica de validação usando Pydantic.
  - `aplicacao_completa.py`: Implementa a aplicação de validação de dados usando Streamlit.
- `app_dashboard.py`: Uma aplicação Streamlit para visualizar KPIs dos dados de campanha.
- `requirements.txt`: Lista as dependências Python necessárias para o projeto.
- `data.csv`: Arquivo de dados de exemplo para testes e demonstração.

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Deivid-Bertapele/ETL-Python-Validando-Dados-e-Excel.git
   cd do seu repositorio
   ```

2. Crie um ambiente virtual e ative-o:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # No Windows
   source .venv/bin/activate  # No macOS/Linux
   ```

3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

### Validação de Dados

1. Execute a aplicação de validação de dados:
   ```bash
   streamlit run src/aplicacao_completa.py
   ```

2. Faça o upload de um arquivo CSV contendo os dados da campanha para validação.

### Dashboard

1. Execute a aplicação do dashboard:
   ```bash
   streamlit run app_dashboard.py
   ```

2. Faça o upload de um arquivo CSV para visualizar os KPIs.

## Dependências

O projeto requer os seguintes pacotes Python:

- `pandas==2.2.3`
- `streamlit==1.43.2`
- `pydantic==2.10.6`
- `plotly==6.0.1`
- ... (e outros conforme listado em `requirements.txt`)





![Captura de tela 2025-03-20 151352](https://github.com/user-attachments/assets/b3d22fa0-32c4-43e2-8c0f-d2de8ad720a5)

![Captura de tela 2025-03-20 153133 - 1](https://github.com/user-attachments/assets/8bff4842-fb25-42f7-94fb-1ccd8324493c)

![Captura de tela 2025-03-20 153133 - 2](https://github.com/user-attachments/assets/7519a1cd-37ec-40b9-adfc-fe3953ac5990)

![Captura de tela 2025-03-20 153229 - 3](https://github.com/user-attachments/assets/1980487d-a313-4edc-87aa-111bd26ebf39)

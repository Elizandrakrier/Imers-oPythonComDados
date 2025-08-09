# 📊 Dashboard de Salários na Área de Dados

Este projeto é um dashboard interativo desenvolvido em [Streamlit](https://streamlit.io/) para análise de salários na área de dados. Ele permite explorar informações salariais por ano, senioridade, tipo de contrato, tamanho da empresa, país e mais.

## Funcionalidades

- **Filtros interativos**: Ano, senioridade, tipo de contrato e tamanho da empresa.
- **KPIs**: Salário médio, salário máximo, total de registros e cargo mais frequente.
- **Gráficos**:
  - Top 10 cargos por salário médio.
  - Distribuição de salários anuais.
  - Proporção dos tipos de trabalho (remoto, presencial, híbrido).
  - Salário médio de Cientista de Dados por país.
- **Tabela detalhada** dos dados filtrados.

## Como rodar o projeto

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/Elizandrakrier/Imers-oPythonComDados.git
   cd Imers-oPythonComDados
   ```

2. **Crie um ambiente virtual (opcional, mas recomendado):**
   ```sh
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Instale as dependências:**
   ```sh
   pip install -r requirements.txt
   ```
   > Se não houver um arquivo `requirements.txt`, instale manualmente:
   ```sh
   pip install streamlit pandas plotly
   ```

4. **Execute o dashboard:**
   ```sh
   streamlit run app.py
   ```

5. **Acesse no navegador:**  
   O Streamlit irá abrir automaticamente, mas você pode acessar manualmente em [http://localhost:8501](http://localhost:8501).

## Fonte dos Dados

Os dados utilizados estão disponíveis em:  
[https://github.com/vqrca/dashboard_salarios_dados](https://github.com/vqrca/dashboard_salarios_dados)

## Exemplo

![Exemplo do dashboard](exemplo_dashboard.png)

## Licença

Este projeto está sob a licença MIT.

---

Desenvolvido por [Elizandra Reis Pereira](https://github.com/Elizandrakrier)

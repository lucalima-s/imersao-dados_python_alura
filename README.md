# 📊 Dashboard de Salários na Área de Dados

> Projeto desenvolvido durante a Imersão de Dados com Python da **Alura**.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28%2B-red)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## 🖥️ Acesso Online

Você pode acessar o dashboard funcionando diretamente pelo navegador, sem precisar instalar nada:

**[Clique aqui para ver o Dashboard](https://imersao-dadospythonalura.streamlit.app/)**

---

## 📝 Sobre o Projeto

Este é um dashboard interativo desenvolvido em **Python** utilizando a biblioteca **Streamlit**. O objetivo da aplicação é analisar e visualizar dados salariais de profissionais da área de dados ao redor do mundo.

Através dele, é possível explorar tendências de mercado, comparar salários por senioridade, tamanho de empresa e localização geográfica.

---

## ⚙️ Funcionalidades

O dashboard oferece as seguintes funcionalidades interativas:

- **Filtros Dinâmicos na Barra Lateral:**
  - Seleção por Ano.
  - Nível de Senioridade (Junior, Mid, Senior, Executive).
  - Tipo de Contrato (Full-time, Freelance, etc.).
  - Tamanho da Empresa (Pequena, Média, Grande).

- **KPIs (Indicadores Chave):**
  - Média Salarial Anual (em USD).
  - Salário Máximo registrado.
  - Total de registros analisados.
  - Cargo mais frequente no filtro selecionado.

- **Visualizações Gráficas (Plotly):**
  - 📊 **Top 10 Cargos:** Gráfico de barras com os maiores salários médios.
  - 📈 **Distribuição Salarial:** Histograma mostrando a frequência das faixas salariais.
  - 🍩 **Modalidade de Trabalho:** Gráfico de rosca mostrando a proporção de trabalho remoto vs. presencial.
  - 🌍 **Mapa Global:** Mapa coroplético exibindo a média salarial de Cientistas de Dados por país.

- **Tabela de Dados:** Visualização completa do dataset filtrado.

---

## 🛠️ Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/) (Interface Web)
- [Pandas](https://pandas.pydata.org/) (Manipulação de Dados)
- [Plotly Express](https://plotly.com/python/plotly-express/) (Visualização de Dados)

---

## 🚀 Como executar o projeto

Caso queira rodar o projeto na sua própria máquina para estudos:

### Pré-requisitos

Antes de começar, certifique-se de ter o **Python** instalado em sua máquina.

### Passo a passo

1. **Clone o repositório:**
   Abra o seu terminal (cmd, PowerShell ou terminal do VS Code) e digite:
   ```bash
   git clone [https://github.com/lucalima-s/imersao-dados_python_alura.git](https://github.com/lucalima-s/imersao-dados_python_alura.git)

2. **Acesse a pasta do projeto:**
    Entre no diretório que acabou de ser criado:
    ```bash
   cd imersao-dados_python_alura

3. **Instale as dependências:**
    Como o arquivo requirements.txt já está no projeto, basta rodar:
    ```bash
   pip install -r requirements.txt

4. **Execute a aplicação:**
    Inicie o servidor do Streamlit com o comando:
    ```bash
   streamlit run app.py

5. **Acesse no navegador:**
    O Streamlit abrirá automaticamente uma aba no seu navegador com o dashboard (geralmente o endereço é http://localhost:8501).

---

## 📢 Conclusão e Aprendizados
- Este projeto foi fundamental para consolidar conhecimentos em:
- Criação de Dashboards Interativos com **Streamlit**.
- Limpeza e filtragem de dados com **Pandas**.
- Storytelling com dados através de gráficos do **Plotly**.

---

## ✒️ Autor
Desenvolvido por Lucas Lima

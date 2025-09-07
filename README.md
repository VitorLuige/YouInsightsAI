# 🚀 YouInsights AI: O Assistente de Análise de Afiliados

> Solução desenvolvida para o Desafio de Inovação do Programa de Estágio YouShop 2025.

---

## 💡 Sobre o Projeto

O **YouInsights AI** é um protótipo de assistente de inteligência artificial generativa criado para resolver uma dor real de empreendedores digitais e afiliados: a dificuldade de transformar dados brutos de desempenho em insights práticos e acionáveis.

A solução atua como um mentor de negócios, interpretando perguntas em linguagem natural e, em seguida, gerando análises de dados e visualizações para comprovar suas conclusões.

## ✨ Funcionalidades

* **IA Generativa:** Utiliza a API do Google Gemini para interpretar perguntas abertas e gerar código Python para análise.
* **Análise de Dados:** Calcula KPIs essenciais como **ROI**, **Taxa de Conversão** e **Comissão Total**.
* **Visualização de Dados:** Gera gráficos (barras, linhas) dinamicamente para provar as conclusões da IA.
* **Fluxo de Trabalho Profissional:** Demonstra o processo completo de análise, da base de dados ao dashboard interativo no Power BI.

---

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Pandas & NumPy:** Para manipulação e análise de dados.
* **Matplotlib:** Para a geração de gráficos dinâmicos.
* **Jupyter Notebook:** Para o ambiente do chatbot interativo.
* **Google Gemini API:** O motor de IA generativa.
* **Power BI:** Para o dashboard de análise final.

---

## 📦 Estrutura do Repositório

* `YouInsights AI.ipynb`: O notebook principal com todo o código do chatbot.
* `Dados.csv`: A base de dados simulada utilizada para a análise.
* `YouShop.pbix`: O arquivo do dashboard interativo do Power BI.
* `.gitignore` & `.env`: Arquivos de configuração para proteger a chave de API.

---

## ▶️ Como Rodar o Projeto

Para testar o chatbot, siga estes passos:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/VitorLuige/YouInsightsAI.git](https://github.com/VitorLuige/YouInsightsAI.git)
    ```
2.  **Instale as bibliotecas:** Crie um ambiente virtual e instale as dependências.
    ```bash
    pip install pandas numpy matplotlib ipywidgets google-generativeai python-dotenv
    ```
3.  **Obtenha sua Chave API:**
    * Crie uma chave para a Google Gemini API.
    * Crie um arquivo chamado **`.env`** no diretório do projeto e adicione a chave: `GOOGLE_API_KEY="SUA_CHAVE_AQUI"`
4.  **Execute o Notebook:**
    * Abra o `YouInsights AI.ipynb` no Jupyter Notebook.
    * Execute todas as células para carregar a IA e o chatbot.
    * O chatbot estará pronto para responder suas perguntas.

---

## 👨‍💻 Contato

* **Nome:** Vítor Luige Peruchi
* **E-mail:** contato.vlp05@gmail.com
* **LinkedIn:** www.linkedin.com/in/vitor-luige-peruchi

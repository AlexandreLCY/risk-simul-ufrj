# Simulador Inteligente de Portfólios com LLM e Monte Carlo

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.25-orange?style=for-the-badge&logo=streamlit)](https://streamlit.io)
[![Status](https://img.shields.io/badge/status-concluído-green?style=for-the-badge)]()

<br>

> Uma ferramenta que criamos para fins academicos que usa IA para "conversar" com o usuário, entender seu perfil e recomendar uma carteira de investimentos personalizada usando Simulação de Monte Carlo.

<br>

## ⚠️ Status do Projeto

**Aviso:** A API de Inteligência Artificial (LLM) que interpreta o perfil do usuário está desativada no momento para evitar altos custos de manutenção, já que este é um projeto de portfólio.

Mas não se preocupe! **Toda a interação e o funcionamento completo do sistema estão gravados na demonstração em vídeo logo abaixo.**

## 🎥 Demonstração em Vídeo

Para ver o projeto em ação, com todas as funcionalidades e ajustes de portfólio, confira o vídeo que preparamos:

[https://youtu.be/eF2gBoM-vMs](https://youtu.be/eF2gBoM-vMs)

## 🎯 Sobre o Projeto

Quem nunca se sentiu um pouco perdido na hora de investir? O mercado financeiro é complexo e nem todo mundo tem tempo ou conhecimento para montar uma carteira que faça sentido para seus objetivos.

Pensando nisso, nosso grupo desenvolveu o Simulador Inteligente de Portfólios. A ideia é simples: uma ferramenta que funciona como um consultor de investimentos pessoal. Você descreve seu perfil e seus objetivos com suas próprias palavras, e nosso sistema, usando um LLM para entender o que você disse e a Simulação de Monte Carlo para calcular os riscos, monta a carteira ideal para você.

## ✨ O que ele faz?

* **🤖 Conversa Inteligente com LLM:** Em vez de formulários chatos, você simplesmente escreve sobre você. O sistema entende e traduz isso em uma estratégia de investimento.
* **📈 Recomendações Sob Medida:** Com base no seu perfil, a ferramenta sugere uma carteira diversificada, explicando o porquê de cada ativo.
* **📊 Análise de Risco de Verdade:** Calculamos métricas que o mercado usa, como **Value at Risk (VaR)**, **Índice de Sharpe** e **Drawdown**, para você saber exatamente onde está pisando.
* **🎨 Gráficos que Falam por Si:** Construímos uma interface interativa com `Streamlit` que mostra tudo de forma visual: **Matriz de Correlação**, **Risco vs. Retorno** e, claro, as simulações.
* **🔄 Seu Portfólio, Suas Regras:** Não gostou de algo? Você pode pedir ajustes e o sistema recalcula tudo na hora, até a carteira ficar do seu jeito.

## 🛠️ Tecnologias Utilizadas

Para dar vida a este projeto, usamos uma combinação de tecnologias de ponta e conceitos sólidos do mercado financeiro:

* **`Langchain`**: A ponte que conecta nosso app a um Large Language Model (LLM) para entender a linguagem do usuário.
* **`Simulação de Monte Carlo`**: O motor matemático por trás das nossas projeções de risco e retorno.
* **`Streamlit`**: Para construir a interface web de forma rápida e interativa, sem precisar ser um expert em front-end.
* **`Pandas` & `NumPy`**: A dupla dinâmica para toda a manipulação e cálculo de dados.
* **`Yahoo Finance` API**: Nossa fonte de dados para obter as cotações históricas dos ativos.

## 🚀 Como Executar o Projeto

Quer testar o simulador na sua máquina? Siga os passos:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/TheoCohenF/risk-simul-ufrj](https://github.com/TheoCohenF/risk-simul-ufrj)
    cd risk-simul-ufrj
    ```

2.  **Crie e ative um ambiente virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Rode a aplicação:**
    ```bash
    streamlit run seu_arquivo_principal.py
    ```

5.  Abra `http://localhost:8501` no seu navegador e comece a simulação!

## 📄 Relatório Acadêmico Completo

Este projeto foi nosso trabalho final para a disciplina de Análise de Risco da UFRJ. Quer ver todos os detalhes acadêmicos, a matemática e a teoria por trás? O relatório completo está aqui:

* **[📄 Ler o Relatório Completo em PDF](./Relatório_Análise_de_Risco.pdf)**

## 👥 A Equipe

Este projeto foi desenvolvido por:

* **Alexandre Pintor da Silva** - `[https://github.com/AlexandreLCY]`
* **Rafael Jordão Clemente** - `[https://github.com/rafaeljc]`
* **Luiz Cláudio Vieira Filho** - `[https://github.com/luizcvfilho]`
* **Theo Cohen Farhat** - `[https://github.com/TheoCohenF]`

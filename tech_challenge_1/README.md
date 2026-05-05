# Análise de NPS e Experiência do Cliente em E-commerce

Este repositório contém uma análise detalhada dos fatores que influenciam o Net Promoter Score (NPS) e a experiência do cliente em uma operação de e-commerce.

## 🎯 Objetivo do Projeto

O objetivo central deste trabalho é responder à seguinte pergunta orientadora: **Quais fatores são mais impactantes no NPS e na experiência do cliente?**

Para isso, a análise investiga como a satisfação do cliente (mensurada pela nota de NPS) correlaciona-se com diversas variáveis da jornada de compra, tais como:
* Perfil demográfico (idade, região);
* Performance logística (atrasos, tempo de entrega);
* Interações de suporte (contatos com atendimento, tempo de resolução);
* Comportamento de compra (valor do pedido, quantidade de itens).

## 📊 Descrição da Base de Dados

Os dados utilizados consistem em um arquivo CSV contendo o histórico de pedidos, entregas e interações com o atendimento ao cliente. As principais variáveis analisadas incluem:

* **Dados do Pedido:** Valor da transação, quantidade de itens e forma de pagamento.
* **Dados Logísticos:** Tempo total de entrega, dias de atraso e número de tentativas de entrega.
* **Dados de Atendimento:** Volume de contatos realizados pelo cliente e tempo de resolução.
* **Indicadores de Negócio:** Nota de satisfação (0-10) e indicadores internos.

## 🧪 Metodologia

A análise seguiu os seguintes passos metodológicos:

1.  **Classificação de NPS:** As notas foram categorizadas no padrão de mercado:
    * **Detratores:** Notas de 0 a 6.
    * **Neutros:** Notas 7 e 8.
    * **Promotores:** Notas 9 e 10.
2.  **Análise Individual de Notas:** Além da classificação, as notas foram analisadas individualmente para identificar padrões granulares de comportamento.
3.  **Análise Exploratória de Dados (EDA):** Utilização de técnicas estatísticas e visualização de dados para descobrir correlações entre as variáveis operacionais e a nota final atribuída pelo cliente.

## 🛠️ Tecnologias e Ferramentas

O projeto foi desenvolvido inteiramente em **Python 3**, utilizando as seguintes bibliotecas:
* `pandas`: Manipulação e tratamento de dados.
* `matplotlib` & `seaborn`: Criação de gráficos estáticos e análises estatísticas visuais.
* `plotly`: Visualizações interativas.
* `warnings`: Gerenciamento de alertas de execução.

## 🚀 Como Reproduzir os Resultados

Você pode executar as análises de duas formas principais:

### 1. Via Google Colab (Recomendado)
A ferramenta original de desenvolvimento foi o Google Colab. 
1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Faça o upload do arquivo `tech1_project.ipynb`.
3. Faça o upload da base de dados (arquivo CSV disponível neste repositório) para o ambiente do Colab.
4. Execute as células sequencialmente.

### 2. Ambiente Local (Python)
Caso prefira rodar localmente:
1. Certifique-se de ter o Python 3 instalado.
2. Clone este repositório:
   ```bash
   git clone [https://github.com/franfrane/fiap-tech-challenges/tree/main/tech_challenge_1](https://github.com/franfrane/fiap-tech-challenges/tree/main/tech_challenge_1)

```markdown
# 🛍️ Análise de Desempenho das Lojas

## 📘 Descrição do Projeto

Este projeto tem como objetivo analisar o desempenho de quatro lojas pertencentes ao Senhor João, com o intuito de identificar qual delas apresenta as melhores condições de mercado e operacionais para ser vendida.  
A análise foi conduzida em **Python**, utilizando as bibliotecas **Pandas** e **Matplotlib**, e engloba indicadores financeiros, operacionais e de satisfação dos clientes.

Os resultados foram sintetizados em um **relatório final** com apoio de visualizações gráficas e interpretações quantitativas.

---

## 🎯 Objetivos da Análise

A análise buscou responder à seguinte questão principal:

> “Qual das quatro lojas apresenta o pior desempenho geral e, portanto, é a melhor candidata para ser vendida?”

Para isso, foram avaliados os seguintes aspectos:

1. **Faturamento total das lojas** – identificação da unidade com maior e menor receita.
2. **Vendas por categoria de produtos** – análise da distribuição de vendas entre diferentes segmentos.
3. **Média das avaliações dos clientes** – mensuração da satisfação geral com o atendimento e produtos.
4. **Produtos mais e menos vendidos** – determinação de itens de maior e menor saída.
5. **Frete médio por loja** – comparação dos custos médios de frete entre as unidades.

---

## 🧩 Base de Dados

Cada loja foi representada por um conjunto de dados independente, contendo as seguintes colunas principais:

- **Produto:** nome do item vendido.  
- **Categoria do Produto:** tipo de produto (ex.: móveis, eletrônicos, brinquedos etc.).  
- **Preço:** valor da venda.  
- **Frete:** custo de envio.  
- **Avaliação da compra:** nota atribuída pelo cliente.

Os dados foram carregados e tratados utilizando o `pandas`, com agrupamentos e agregações para extração dos indicadores de desempenho.

---

## 📊 Principais Resultados

### 💰 Faturamento Total
A **Loja 1** apresentou o **maior faturamento** (R$ 1.534.509,12), enquanto a **Loja 4** registrou o menor (R$ 1.384.497,58).

### 🛒 Vendas por Categoria
As categorias **“móveis”** e **“eletrônicos”** foram as mais vendidas em todas as lojas, demonstrando uma tendência consistente de consumo.

### ⭐ Avaliações dos Clientes
A **Loja 3** destacou-se com a **melhor média de avaliação** (4,05), indicando maior satisfação e fidelização dos consumidores.

### 📦 Produtos Mais e Menos Vendidos
Cada loja apresentou variações em seus produtos de destaque, mas de forma geral, itens de maior valor agregado, como **TVs, camas e móveis**, foram os mais procurados.

### 🚚 Frete Médio
A **Loja 4** teve o **menor frete médio** (R$ 31,28), embora isso não tenha se refletido em melhor desempenho geral de vendas ou faturamento.

---

## 🧾 Conclusão

Após a análise dos indicadores e das visualizações, conclui-se que a **Loja 3** apresenta o melhor desempenho geral, combinando **avaliações elevadas**, **vendas equilibradas por categoria** e **frete competitivo**.

Por outro lado, a **Loja 4** é a unidade com **pior desempenho agregado**, apresentando o **menor faturamento**, **avaliações medianas** e **menor presença em categorias de alto valor agregado**.

> ✅ **Recomendação:** O Senhor João deve **vender a Loja 4**, pois é a menos rentável e possui o menor potencial de crescimento entre as quatro unidades analisadas.

---

## 🧠 Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas** – manipulação e análise de dados.  
- **Matplotlib** – geração dos gráficos e visualizações.  
- **Jupyter/Google Colab** – ambiente de desenvolvimento interativo.

---

## 🗂️ Estrutura do Projeto

```

📦 analise-lojas
├── 📁 dados/                # Arquivos CSV ou TXT de cada loja
├── 📁 imagens/              # Gráficos gerados (opcional)
├── 📄 analise_lojas.ipynb   # Notebook principal com o código completo
├── 📄 relatorio_final.md    # Relatório técnico em Markdown
└── 📄 README.md             # Este arquivo

```

---

## 🧑‍💻 Autor

**Lissandro Sousa**  
Estudante de Finanças – Universidade Federal do Ceará (UFC)  
Contato: [LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)

---

## 📄 Licença

Este projeto está sob a licença **MIT**.  
Sinta-se à vontade para utilizar, adaptar e compartilhar o conteúdo, desde que citada a fonte original.

---

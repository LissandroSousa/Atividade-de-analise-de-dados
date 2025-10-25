```markdown
# 🛍️ Análise de Desempenho das Lojas do Sr. João

## 📖 Descrição do Projeto

Este projeto tem como objetivo analisar o desempenho de **quatro lojas pertencentes ao Sr. João**, a fim de identificar **qual delas apresenta melhores condições de mercado e operacionais** e **qual deve ser vendida**.  
A análise foi realizada com base em dados de vendas, categorias de produtos, avaliações de clientes e custos médios de frete, utilizando **Python**, **pandas** e **matplotlib**.

O estudo visa fornecer uma **decisão fundamentada em dados (data-driven decision)**, integrando estatísticas descritivas e visualizações gráficas.

---

## 🎯 Objetivos

- Calcular o **faturamento total** de cada loja.  
- Avaliar o **desempenho por categoria de produto**.  
- Determinar a **média das avaliações** dos clientes.  
- Identificar **produtos mais e menos vendidos**.  
- Calcular o **frete médio** por loja.  
- Gerar **gráficos e visualizações** para apoio à tomada de decisão.  
- Elaborar um **relatório conclusivo** indicando a loja que deve ser vendida.

---

## 🧰 Tecnologias Utilizadas

- **Linguagem:** Python  
- **Bibliotecas Principais:**
  - `pandas` → manipulação e análise de dados
  - `matplotlib` → geração de gráficos
  - `numpy` → cálculos numéricos
- **Ambiente de execução:** Google Colab ou Jupyter Notebook  

---

## 📂 Estrutura do Projeto

```

📁 analise-lojas
├── dados/
│   ├── loja1.csv
│   ├── loja2.csv
│   ├── loja3.csv
│   └── loja4.csv
├── graficos/
│   ├── faturamento.png
│   ├── categorias.png
│   ├── avaliacoes.png
│   ├── produtos.png
│   └── frete.png
├── analise_lojas.ipynb        # Notebook principal da análise
├── relatorio_final.md         # Relatório conclusivo em formato Markdown
└── README.md                  # Este arquivo

```

---

## 📈 Análises Realizadas

### 1. Faturamento Total
O cálculo do faturamento foi feito por meio da soma dos valores da coluna `"Preço"` de cada base de dados.  
**Resultado:**
| Loja | Faturamento (R$) |
|------|------------------|
| Loja 1 | 1.534.509,12 |
| Loja 2 | 1.488.459,06 |
| Loja 3 | 1.464.025,03 |
| Loja 4 | 1.384.497,58 |

### 2. Vendas por Categoria
Foram agrupados os produtos por categoria para identificar as mais vendidas.  
As categorias de **móveis** e **eletrônicos** lideram as vendas em todas as lojas.

### 3. Avaliação Média
A **Loja 3** apresentou a **melhor média de avaliação** (4,05), indicando maior satisfação dos clientes.

### 4. Produtos Mais e Menos Vendidos
Cada loja apresentou seus produtos mais e menos comercializados, sendo observada predominância de itens de maior valor agregado nos primeiros.

### 5. Frete Médio
A **Loja 4** teve o **menor custo médio de frete (R$ 31,28)**, embora apresente o menor faturamento geral.

---

## 📊 Visualizações Gráficas

Os gráficos foram gerados com `matplotlib`, contemplando:

- Faturamento Total por Loja  
- Vendas por Categoria  
- Média de Avaliações  
- Produtos Mais e Menos Vendidos  
- Frete Médio  

Cada gráfico foi configurado com eixos, títulos e grades para melhor interpretação visual.

---

## 🧩 Conclusão e Recomendação

Após as análises, concluiu-se que:

- A **Loja 1** possui o **maior faturamento**, mas avaliações ligeiramente inferiores.  
- A **Loja 3** apresenta **melhor equilíbrio geral**: boa receita, excelente avaliação e frete competitivo.  
- A **Loja 4** tem **baixo faturamento e desempenho inferior**, apesar do frete mais baixo.

📌 **Recomendação final:**  
> O Sr. João deve **vender a Loja 4**, pois é a menos rentável e apresenta menor potencial de crescimento em comparação com as demais.

---

## 🧑‍💻 Autor

**Lissandro Sousa**  
Estudante de Finanças | Universidade Federal do Ceará (UFC)  
Desenvolvedor em Python e R com foco em análise de dados, econometria e modelagem financeira.  

📧 Contato: [lissandrosousa@email.com](mailto:lissandrosousa@email.com)

---

## 📜 Licença

Este projeto é distribuído sob a licença **MIT License**.  
Sinta-se livre para usar, modificar e compartilhar, desde que os créditos sejam mantidos.

---

## ⭐ Como Citar

Se desejar referenciar este repositório em um trabalho acadêmico:

> SOUSA, Lissandro. *Análise de Desempenho das Lojas do Sr. João*. Fortaleza: Universidade Federal do Ceará, 2025. Disponível em: [https://github.com/usuario/analise-lojas](https://github.com/usuario/analise-lojas). Acesso em: dd mmm. aaaa.
```

# 📊 Análise de Redes Complexas: Comparação entre Grafos Sintéticos e Reais

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como trabalho final da disciplina de Grafos e Redes Complexas, com o objetivo de investigar propriedades estruturais de diferentes modelos de redes e compará-las com uma rede real.

A análise foi realizada utilizando conceitos da Teoria dos Grafos e da Ciência das Redes Complexas, explorando métricas topológicas, características de conectividade, centralidade e propriedades emergentes observadas em diferentes tipos de redes.

---

## 🎯 Objetivos

O trabalho foi dividido em duas etapas principais:

### Parte 1 — Análise de Grafos Sintéticos

Foram geradas redes artificiais utilizando três modelos clássicos:

* Barabási-Albert (Scale-Free)
* Watts-Strogatz (Small World)
* Erdős-Rényi (Aleatório)

Para reduzir vieses amostrais, foram utilizadas diferentes configurações e sementes aleatórias.

O objetivo foi analisar o comportamento de diversas métricas estruturais e responder questões de pesquisa baseadas em evidências obtidas experimentalmente.

#### Questões Investigadas

**1. Qual modelo apresenta maior coeficiente de agrupamento (Clustering Coefficient)?**

Análise comparativa do agrupamento local entre os diferentes modelos.

**2. Redes livres de escala tendem a ser dissortativas?**

Investigação da assortatividade em redes Barabási-Albert.

**3. Qual modelo apresenta menores caminhos médios?**

Comparação da eficiência de navegação entre os modelos analisados.

---

### Parte 2 — Comparação com uma Rede Real

Foi selecionada uma rede real proveniente do repositório Network Repository.

A partir dela foram realizadas comparações com versões sintéticas equivalentes, buscando responder:

* A rede apresenta características de rede livre de escala?
* A rede possui propriedades Small World?
* A rede se comporta como uma rede aleatória?
* Quais são os vértices mais importantes da rede?
* A rede é robusta a falhas?
* A difusão de informação é eficiente?
* A preservação de informação é favorecida?
* A navegação na rede é simples?

---

## 📈 Métricas Analisadas

Durante o projeto foram calculadas diversas métricas clássicas de redes complexas:

### Estrutura Global

* Número de vértices
* Número de arestas
* Grau médio
* Densidade
* Diâmetro

### Agrupamento

* Clustering Coefficient
* Transitividade

### Conectividade

* Comprimento médio dos caminhos
* Distribuição dos graus

### Correlação Estrutural

* Assortatividade

### Centralidade

* Betweenness Centrality

---

## 🛠️ Tecnologias Utilizadas

### Linguagem

* Python 3

### Bibliotecas

* NetworkX
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## 📂 Estrutura do Projeto

```text
.
├── data/
│   ├── redes_reais/
│   └── redes_sinteticas/
│
├── notebooks/
│   └── analise_redes.ipynb
│
├── figures/
│   ├── clustering/
│   ├── assortatividade/
│   ├── caminhos_medios/
│   └── comparacoes/
│
├── README.md
└── requirements.txt
```

---

## 🔬 Metodologia

### Geração das Redes Sintéticas

Os grafos sintéticos foram gerados utilizando os modelos:

* Erdős-Rényi
* Barabási-Albert
* Watts-Strogatz

Para cada configuração foram utilizadas diferentes sementes aleatórias, permitindo uma análise estatisticamente mais confiável.

### Comparação com Rede Real

A rede real foi analisada utilizando as mesmas métricas aplicadas aos grafos sintéticos.

Posteriormente foram criadas versões sintéticas equivalentes com número semelhante de vértices e conectividade comparável, permitindo uma comparação estrutural mais justa.

---

## 📊 Principais Resultados

Entre os resultados observados destacam-se:

* Diferenças significativas de clustering entre os modelos.
* Evidências de dissortatividade em redes Barabási-Albert.
* Diferenças nos comprimentos médios dos caminhos.
* Identificação dos vértices mais influentes da rede real.
* Análise do comportamento da rede real em relação às propriedades Scale-Free e Small World.

---

## 🚀 Como Executar

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/network-science-final-project.git
```

### 2. Instalar dependências

```bash
pip install -r requirements.txt
```

### 3. Executar o notebook

Abra o notebook principal:

```bash
jupyter notebook
```

ou

```bash
jupyter lab
```

---

## 📚 Conceitos Envolvidos

Este projeto utiliza conceitos de:

* Teoria dos Grafos
* Redes Complexas
* Redes Livre de Escala (Scale-Free)
* Redes Small World
* Assortatividade
* Centralidade
* Análise de Redes Reais
* Ciência de Dados

---

## 👥 Autores

* Francisco da Silva Bueno Junior - 25008051
* Isabel Baungartner - 25001436
* Julia de Souza Leandro - 25009148
* Tiago Noda Von Zuben - 25018493

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido para a disciplina de Grafos e Redes Complexas, com foco na análise experimental de redes sintéticas e reais utilizando métricas estruturais e conceitos da Ciência das Redes.

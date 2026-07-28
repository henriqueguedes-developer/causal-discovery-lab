# 🔎 Causal Investigation Lab

### Investigando relações de causa e efeito utilizando Causal Discovery

Uma POC prática mostrando como técnicas de **Causal Discovery** podem ser utilizadas para investigar problemas de negócio além da simples correlação.

O projeto utiliza um cenário de **churn de clientes** para demonstrar como diferentes algoritmos podem gerar hipóteses causais, comparar grafos, estimar efeitos e validar resultados utilizando Python.

---

## 🎯 Objetivo

Em projetos reais, perguntas como estas são muito comuns:

* Clientes que abrem mais tickets cancelam mais?
* NPS realmente influencia retenção?
* Uma funcionalidade aumenta fidelização?
* O onboarding reduz churn?
* Existe alguma variável escondida afetando o resultado?

Análises tradicionais normalmente respondem:

> **"O que acontece junto?"**

Este projeto tenta responder:

> **"O que realmente pode influenciar o resultado?"**

---

## 🧠 Conceitos explorados

Este notebook aborda conceitos importantes como:

* Correlação × Causalidade
* DAG (Directed Acyclic Graph)
* Causal Discovery
* PC Algorithm
* GES (Greedy Equivalence Search)
* Confounders
* Estimativa de efeito causal
* Refutation Tests
* Interpretação de grafos causais

---

## 🚀 O que você encontrará neste projeto

### ✔ Geração de dados sintéticos

Criação de um cenário controlado simulando churn de clientes.

### ✔ Ground Truth

Construção manual do DAG verdadeiro utilizado como referência.

### ✔ Descoberta Causal

Aplicação dos algoritmos:

* PC Algorithm
* GES

Comparando os resultados encontrados com a estrutura causal original.

### ✔ Estimativa de Efeito Causal

Uso da biblioteca **DoWhy** para estimar efeitos causais entre variáveis.

### ✔ Comparação com Modelos Tradicionais

Comparação entre:

* Regressão logística
* Correlação
* Análise causal

### ✔ Refutation Tests

Testes para avaliar robustez dos resultados.

### ✔ Variáveis Ocultas

Simulação de cenários mais próximos do mundo real.

---

## 📂 Estrutura do projeto

```text
.
├── poc_causal_discovery_churn.ipynb
├── THE_CHURN_DOSSIER.pdf
├── README.md
└── assets/
```

---

## 🛠 Tecnologias utilizadas

* Python
* Jupyter Notebook
* Google Colab
* Pandas
* NumPy
* Matplotlib
* NetworkX
* Scikit-learn
* DoWhy
* Causal Discovery

---

## ▶ Como executar

Clone o projeto:

```bash
git clone git@github.com:henriqueguedes-developer/causal-investigation-lab.git
```

Entre na pasta:

```bash
cd causal-investigation-lab
```

Abra o notebook:

* Google Colab
* Jupyter Notebook

Execute as células na ordem.

---

## 💡 Possíveis aplicações

Embora o exemplo utilize churn, a mesma abordagem pode ser aplicada para investigar perguntas como:

* Uma funcionalidade realmente aumenta retenção?
* Um programa de fidelidade reduz cancelamentos?
* O treinamento melhora satisfação?
* O NPS realmente influencia retenção?
* Quais fatores merecem investigação antes de uma decisão estratégica?

---

## ⚠ Limitações

Esta POC possui caráter educacional.

Os resultados representam hipóteses causais dentro do cenário construído.

Em ambientes reais, recomenda-se combinar:

* Conhecimento do negócio
* Dados reais
* Validação estatística
* Experimentos controlados
* Especialistas do domínio

---

## 👨‍💻 Autor

### Luís Henrique 

Desenvolvedor com foco em:

* Python
* Node.js
* Inteligência Artificial
* Machine Learning
* Engenharia de Software

Gosto de transformar problemas complexos em soluções práticas utilizando dados, IA e arquitetura de software.

---

## 💼 LinkedIn

👉 https://www.linkedin.com/in/luishguedes/

Compartilho projetos, estudos e experimentos envolvendo IA aplicada a problemas reais.

---

## 🤝 Contribuições

Sugestões, melhorias e novos estudos são bem-vindos.

Sinta-se à vontade para abrir uma Issue ou enviar um Pull Request.

---

## ⭐ Gostou do projeto?

Se este projeto foi útil para você, deixe uma ⭐ no repositório.

Isso ajuda outras pessoas interessadas em IA, Machine Learning e Causal Discovery a encontrarem este material.

---

> *"A melhor decisão não nasce da maior quantidade de opiniões. Ela nasce das melhores evidências."*

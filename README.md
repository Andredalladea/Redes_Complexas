# Redes Complexas Aplicadas ao Aprendizado de Máquina

Projeto desenvolvido para a disciplina de Redes Complexas da Universidade de São Paulo (USP).

## 📖 Sobre o projeto

Este trabalho investiga como conceitos de Redes Complexas podem ser aplicados em problemas de Aprendizado de Máquina.

Como estudo de caso, foi utilizado o conjunto de dados **Breast Cancer Wisconsin**, disponível na biblioteca Scikit-Learn. Os atributos do dataset são representados como uma rede baseada em correlações, permitindo aplicar métricas topológicas para selecionar os atributos mais relevantes para classificação. :contentReference[oaicite:1]{index=1}

---

## 🎯 Objetivos

- Construir uma rede baseada na correlação entre atributos;
- Aplicar métricas de centralidade;
- Selecionar atributos relevantes;
- Comparar o desempenho de modelos de classificação;
- Avaliar o impacto do threshold na construção da rede;
- Detectar comunidades de atributos.

---

## 🛠 Tecnologias Utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- NetworkX
- Scikit-Learn
- Matplotlib

---

## 📂 Estrutura do Projeto

O notebook realiza as seguintes etapas:

1. Carregamento e preparação dos dados;
2. Classificação tradicional (SVM e Random Forest);
3. Construção da Rede Complexa;
4. Visualização da rede;
5. Cálculo das métricas de centralidade;
6. Seleção de atributos utilizando:
   - Degree Centrality
   - Betweenness Centrality
   - Eigenvector Centrality
7. Detecção de comunidades;
8. Análise de sensibilidade do threshold;
9. Comparação dos resultados.

---

## 📊 Resultados

Foram comparados diferentes métodos de seleção de atributos utilizando métricas de Redes Complexas.

| Método | Accuracy |
|---------|---------:|
| SVM Original | **97,66%** |
| Degree Centrality | 91,23% |
| Betweenness Centrality | 92,40% |
| Eigenvector Centrality | **94,74%** |

Os resultados mostram que a seleção de atributos baseada em Redes Complexas consegue reduzir a dimensionalidade mantendo um desempenho próximo ao modelo original. :contentReference[oaicite:2]{index=2}

---

## 📚 Referência

Este projeto foi inspirado no artigo:

> **Combining Complex Networks and Data Mining: Why and How**
>
> Luciano da Fontoura Costa et al.

---

## 👨‍💻 Autor

**André Dalla Déa Trombini**

Graduando em Sistemas de Informação – Universidade de São Paulo (USP)

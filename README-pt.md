# Prevendo o Câncer de Mama com Machine Learning

[🇺🇸 English Version](README.md)

Modelo de machine learning que prevê câncer de mama utilizando microRNA como parâmetro de classificação. Este projeto demonstra a aplicação de diversos algoritmos de ML e técnicas de análise de dados para enfrentar um desafio crítico da área da saúde.

## 🎯 Visão Geral do Projeto

O câncer de mama é um dos cânceres mais comuns que afetam mulheres em todo o mundo. Este projeto utiliza dados de microRNA para construir modelos preditivos que podem auxiliar na detecção precoce e diagnóstico. A abordagem combina análise exploratória de dados, engenharia de features e múltiplos algoritmos de machine learning para alcançar performance otimizada.

## 📊 Dataset

- **Fonte:** Dados de expressão de microRNA para classificação de câncer de mama
- **Features:** Níveis de expressão de microRNA
- **Target:** Classificação binária (Maligno/Benigno)
- **Objetivo:** Prever ocorrência de câncer de mama baseado em padrões de microRNA

## 🔬 Pipeline de Desenvolvimento

### 1. **Importação de Dados e Configuração de Bibliotecas**
- Carregamento de bibliotecas essenciais para manipulação de dados e ML
- Importação e inspeção inicial do dataset

### 2. **Análise Exploratória dos Dados (EDA)**
- Resumo estatístico e análise de distribuição dos dados
- Análise de correlação entre features
- Visualização de dados e identificação de padrões

### 3. **Estabelecimento de Baseline Comparativo**
- Criação de baseline comparativo para avaliação de modelos
- Definição de benchmarks de performance

### 4. **Criação de Pipeline**
- Pipeline de pré-processamento de dados
- Escalonamento e transformação de features
- Configuração de validação cruzada

### 5. **Desenvolvimento de Modelos**
- Implementação de múltiplos algoritmos de ML
- Ajuste de hiperparâmetros e otimização
- Comparação e seleção de modelos

### 6. **Análise de Componentes Principais (PCA)**
- Técnicas de redução de dimensionalidade
- Análise de importância de features
- Explicação de variância e visualização

### 7. **Avaliação Experimental**
- Resultados de validação cruzada
- Comparação de métricas de performance
- Testes de significância estatística

### 8. **Avaliação Final de Performance do Modelo**
- Avaliação final do modelo no conjunto de teste
- Métricas de performance abrangentes
- Interpretação do modelo e insights

## 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-%235C7DA2.svg?style=for-the-badge&logo=seaborn&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Plotly](https://img.shields.io/badge/Plotly-%23ffffff.svg?style=for-the-badge&logo=plotly&logoColor=black)

## 📈 Características Principais

- **EDA Abrangente:** Análise aprofundada dos padrões de expressão de microRNA
- **Múltiplos Modelos ML:** Comparação de diversos algoritmos para performance otimizada
- **Engenharia de Features:** Pré-processamento avançado e redução de dimensionalidade
- **Validação Cruzada:** Metodologia robusta de avaliação de modelos
- **Visualização:** Gráficos interativos e visualização abrangente de dados

## 🚀 Como Começar

### Pré-requisitos
```bash
pip install pandas numpy scikit-learn matplotlib seaborn plotly
```

## Uso
- Clone o repositório
- Instale as dependências necessárias
- Execute o notebook Jupyter
- Siga a análise passo a passo

## 📊 Resultados
O modelo alcança alta precisão na previsão de câncer de mama baseado em dados de expressão de microRNA, demonstrando o potencial do machine learning em aplicações de saúde.

## 🤝 Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para submeter um Pull Request.

## 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.

##🙏 Agradecimentos
- Profissionais de saúde e pesquisadores na área de detecção de câncer
- Comunidade open-source por fornecer excelentes bibliotecas de ML
- Contribuidores para datasets de pesquisa de microRNA

---

💡 "Machine Learning na saúde: Transformando dados em insights que salvam vidas."

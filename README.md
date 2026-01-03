# Análise de Sobrevivência e Confiabilidade - UFPR

Este repositório contém o trabalho prático desenvolvido para a disciplina de Análise de Sobrevivência. O objetivo central é analisar dados onde a variável resposta é o **tempo até a ocorrência de um evento** (falha, óbito, cancelamento), lidando adequadamente com observações censuradas.



## 🛠️ Conteúdo Técnico

O projeto explora as três abordagens fundamentais da análise de sobrevivência:

### 1. Análise Não Paramétrica
* **Estimador Kaplan-Meier:** Construção de curvas de sobrevivência $S(t)$ para estimar a probabilidade de não ocorrência do evento ao longo do tempo.
* **Teste de Log-Rank:** Comparação estatística de curvas de sobrevivência entre diferentes grupos (ex: Tratamento A vs Tratamento B).

### 2. Modelagem Semiparamétrica (Regressão)
* **Modelo de Riscos Proporcionais de Cox:** Avaliação do impacto de múltiplas covariáveis no risco (hazard) de ocorrência do evento.
* **Interpretação de Hazard Ratios (HR):** Análise da razão de riscos (ex: "o risco do evento é x vezes maior no grupo exposto").

### 3. Diagnóstico do Modelo
* **Resíduos de Schoenfeld:** Verificação da suposição de proporcionalidade dos riscos ao longo do tempo.
* **Resíduos de Martingale/Deviance:** Avaliação da qualidade do ajuste e identificação de *outliers*.

---

## 🚀 Tecnologias e Implementação

* **Linguagem:** R.
* **Pacotes Principais:** `survival` (modelagem core) e `survminer` (visualização de curvas KM).
* **Relatórios:** Documentação gerada em R Markdown com interpretação clínica/técnica dos resultados.

---

## 📂 Estrutura de Arquivos

* [TrabalhoSobrevivencia.Rmd](./TrabalhoSobrevivencia.Rmd): Código fonte contendo o ajuste dos modelos e testes de hipóteses.
* [TrabalhoSobrevivencia.pdf](./TrabalhoSobrevivencia.pdf): Relatório final com as curvas de sobrevivência plotadas e conclusões do estudo.

---
**Autor:** Luiz Henrique Barretta Francisco  
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*

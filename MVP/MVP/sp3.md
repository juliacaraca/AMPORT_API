# 📊 Sprint 3: Diagnóstico Avançado, Operações de Apoio e Eficiência — AMPORT

Este arquivo contém o detalhamento exclusivo do backlog e requisitos para a **Sprint 3** do projeto AMPORT.

---

## 🎯 Objetivo da Sprint
Enriquecer o dashboard com inteligência analítica avançada e ferramentas de tomada de decisão para alta gestão (Gestores e Analistas seniores), com foco no diagnóstico profundo de ineficiências operacionais, detalhamento de contêineres e rankings comparativos de infraestrutura.

---

## 🔑 User Stories (Backlog da Sprint 3)

### **Rank 6 [US6] - Análise de Top N Motivos de Paradas Portuárias**
* **User Story:** Como analista, quero identificar os "Top N" motivos de paradas portuárias para entender as causas de ineficiência.
* **Prioridade:** Média
* **Esforço:** 8 pontos
* **Requisito do Parceiro:** Gráfico de barras com os principais motivos de parada e filtro por período do ano.
* **Critérios de Aceitação:**
  * Gráfico de barras (horizontal ou vertical) ordenado de forma decrescente pelos motivos que mais geram tempo de ociosidade/parada.
  * Parâmetro dinâmico para o usuário escolher o valor de "N" (Ex: Top 5, Top 10, Top 15).
  * Filtro temporal acoplado para analisar as paradas por trimestres ou meses específicos do ano.

### **Rank 7 [US7] - Relação Navio x Quantidade de Contêineres**
* **User Story:** Como gestor, quero visualizar a quantidade de contêineres por navio e o conteúdo transportado para acompanhar a operação portuária de forma detalhada.
* **Prioridade:** Alta
* **Esforço:** 8 pontos
* **Requisito do Parceiro:** Dashboard com relação navio x quantidade de contêineres e detalhamento do tipo/conteúdo transportado.
* **Critérios de Aceitação:**
  * Visualização analítica cruzando o nome/registro do navio com o volume de TEUs (Unidades equivalentes a 20 pés) movimentados.
  * Tooltip ou gráfico secundário detalhando o mix de mercadorias contidas nesses contêineres (Ex: carga refrigerada, químicos, manufaturados).

### **Rank 8 [US8] - Paradas Vinculadas às Operações de Apoio**
* **User Story:** Como analista, quero visualizar as principais paradas vinculadas às operações de apoio e seus respectivos tipos de operação para identificar gargalos operacionais.
* **Prioridade:** Média
* **Esforço:** 8 pontos
* **Requisito do Parceiro:** Gráfico com classificação das principais paradas em operações de apoio e filtro por tipo de operação.
* **Critérios de Aceitação:**
  * Isolamento dos dados referentes a serviços de apoio portuário (praticagem, rebocadores, amarração).
  * Gráfico de distribuição identificando gargalos específicos dessas categorias de suporte.

### **Rank 9 [US9] - Ranking de Eficiência de Terminais (Movimentação vs. Infraestrutura)**
* **User Story:** Como gestor, quero um ranking de eficiência dos terminais baseado na movimentação vs infraestrutura instalada.
* **Prioridade:** Alta
* **Esforço:** 8 pontos
* **Requisito do Parceiro:** Visualização de Ranking por eficiência comparativa entre diferentes terminais.
* **Critérios de Aceitação:**
  * Cálculo de uma métrica de eficiência que pondere o volume total movimentado em relação à capacidade nominal ou tamanho físico do terminal (ex: toneladas por metro linear de cais).
  * Exibição em formato de tabela de classificação (Leaderboard) interativa com destaque visual para os terminais de melhor e pior desempenho.

---

## 📈 Métricas de Validação da Sprint 3
* **Acurácia do Diagnóstico:** Consistência nas fórmulas de cálculo de eficiência cruzadas com os dados originais da ANTAQ (Meta: 100% de precisão matemática).
* **Granularidade da Informação:** Capacidade de descer do nível macro (Terminal) para o micro (Navio/Contêiner) sem perda de contexto técnico.
* **Tempo de Geração do Ranking:** O cálculo da matriz de eficiência vs infraestrutura deve ser pré-processado na base para garantir performance de renderização.

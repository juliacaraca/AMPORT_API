# 🚀 Sprint 2: Interatividade, Responsividade e Filtros de Mercado — AMPORT

Este arquivo contém o detalhamento exclusivo do backlog e requisitos para a **Sprint 2** do projeto AMPORT.

---

## 🎯 Objetivo da Sprint
Evoluir a fundação criada na Sprint 1, transformando o painel estático em uma interface intuitiva, responsiva e interativa que permita aos investidores e usuários realizarem análises segmentadas por tipo de carga e comportamento histórico do mercado.

---

## 🔑 User Stories (Backlog da Sprint 2)

### **Rank 3 [US3] - Evolução Mensal da Carga Transportada**
* **User Story:** Como investidor, quero ver a evolução mensal da quantidade de carga transportada para prever tendências de mercado.
* **Prioridade:** Baixa
* **Esforço:** 8 pontos
* **Requisito do Parceiro:** Gráfico de linha demonstrando a evolução das movimentações por mês.
* **Critérios de Aceitação:**
  * O gráfico deve exibir o volume histórico em toneladas agrupado mensalmente.
  * Deve conter linhas de tendência ou marcadores claros para facilitar a identificação de sazonalidades.
  * O eixo temporal deve permitir a escala por anos/meses de forma legível.

### **Rank 4 [US4] - Interface Intuitiva e Responsiva**
* **User Story:** Como cliente, quero que a interface seja intuitiva e responsiva para facilitar o acesso em diferentes dispositivos.
* **Prioridade:** Alta
* **Esforço:** 8 pontos
* **Requisito do Parceiro:** Navegação com poucos cliques e layout adaptável (Sistema responsivo).
* **Critérios de Aceitação:**
  * O layout do dashboard deve se ajustar automaticamente a telas de desktops, tablets e smartphones (Mobile-friendly).
  * A navegação principal deve permitir o acesso a qualquer métrica com no máximo 3 cliques.
  * O tempo de carregamento dos componentes visuais deve respeitar os limites de usabilidade estabelecidos.

### **Rank 5 [US5] - Filtros Segmentados por Carga e Terminal**
* **User Story:** Como usuário, quero filtrar os dados por tipo de carga e terminal para realizar análises segmentadas.
* **Prioridade:** Baixa
* **Esforço:** 8 pontos
* **Requisito do Parceiro:** Implementação de filtros interativos e busca personalizada por terminal.
* **Critérios de Aceitação:**
  * Inclusão de um menu contendo filtros dinâmicos de "Tipo de Carga" (Granel Sólido, Granel Líquido, Conteinerizada, etc.) e "Terminal".
  * Ao aplicar um filtro, todos os gráficos da tela (incluindo o gráfico de linha da US3) devem se atualizar instantaneamente.
  * Disponibilização de um campo de busca por texto preditivo para localização rápida de terminais específicos.

---

## 📈 Métricas de Validação da Sprint 2
* **Responsividade:** Garantia de 100% dos elementos visíveis e sem quebra de layout em resoluções de 1920x1080 (Desktop) até 375x812 (Mobile).
* **Tempo de Resposta dos Filtros:** O recarregamento dos dados na tela após a aplicação de um filtro não deve ultrapassar 1.5 segundos.
* **Taxa de Cliques (Usabilidade):** Sucesso na realização de análises cruzadas em menos de 3 interações.

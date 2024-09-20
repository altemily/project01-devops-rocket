# Implementação de Práticas DevOps na Tech

A **Tech**, uma empresa de desenvolvimento de software, busca melhorar seus processos de entrega e operações por meio da implementação de práticas DevOps. Este documento sugere como a empresa pode adotar a filosofia DevOps utilizando os princípios de CALMS e as Três Maneiras.

## Etapas do Projeto

### 1. Diagnóstico Cultural (C de CALMS)

**Processo Identificado:** Entrega e Deploy de Código

**Descrição do Processo Atual:**
- Os desenvolvedores preparam pacotes de implantação manualmente e os enviam para operações.
- O deploy é realizado manualmente e não segue um procedimento padronizado, levando a uma baixa taxa de sucesso, atingindo apenas 80% do esperado.
- Testes manuais são realizados após o deploy, o que gera retrabalho e aumenta o tempo de resolução de incidentes, causando gargalos na entrega das novas features.

**Pontos de Atrito:**
- Falta de comunicação entre as equipes de desenvolvimento e operações.
- Atrasos e falhas frequentes no deploy.
- Retrabalho devido à falta de testes automáticos.

**Oportunidades de Melhoria:**
- Implementar um pipeline de CI/CD.
- Promover reuniões regulares entre as equipes para melhorar a colaboração.
- Feedback individual e em equipes, visando uma maior colaboração interna.

### 2. Automação (A de CALMS)

**Solução Proposta:** Pipeline de CI/CD

**Plano de Implementação:**
1. **Escolha de Ferramentas:** Utilizar Jenkins para automação de build e deploy.
2. **Configuração do Ambiente:** Criar ambientes de desenvolvimento, testes e produção, garantindo que os testes sejam executados em cada build.
3. **Treinamento:** Realizar workshops sobre CI/CD para as equipes.
4. **Implementação Gradual:** Começar com o sistema de gestão de vendas, depois expandir para a plataforma de e-commerce.

**Minimização de Resistências:**
- Envolver equipes nas decisões sobre ferramentas, promovendo uma maior interação dos envolvidos.
- Mostrar benefícios por meio de dados e casos de sucesso.

### 3. Mensuração e Compartilhamento de Conhecimento (M e S de CALMS)

**Métricas Relevantes:**
- Tempo entre entrega e deploy: Reduzir para 11 horas.
- Taxa de sucesso dos deploys: Aumentar para 97%.
- Número de incidentes após o deploy: Reduzir para 1 por semana.
- MTTR de incidentes: Reduzir para 2 horas.

**Plano de Disseminação de Conhecimento:**
1. **Documentação:** Criar um wiki com práticas e processos, para que toda equipe tenha acesso a ele no repositório.
2. **Reuniões Mensais:** Discutir resultados e melhorias, além de feedbacks 360.
3. **Canal de Comunicação:** Estabelecer um Slack para dúvidas e sugestões.

### 4. Três Maneiras 

**Primeira Maneira (Acelerar o Fluxo):**
- Criar um pipeline CI/CD para acelerar a entrega de valor.

**Segunda Maneira (Ampliar o Feedback):**
- Implementar revisões de código e testes automatizados, integrando feedback contínuo.

**Terceira Maneira (Experimentar e Aprender):**
- Estabelecer um ambiente de testes A/B, encorajando a experimentação e aprendizado com falhas.

## Resultados Esperados

A implementação das práticas DevOps na Tech deverá levar a uma maior eficiência nos processos de entrega, um aumento na qualidade do código e uma cultura de colaboração entre as equipes. As métricas estabelecidas permitirão avaliar o impacto das mudanças, e o compartilhamento de conhecimento garantirá a continuidade do aprendizado e melhorias.





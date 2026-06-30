# Business Context — InoClear AI

> Este documento consolida a visão original do produto e os aprendizados obtidos nas entrevistas e respostas do cliente no documento "Perguntas Sprint 1 - Desafio A - RH". Ele passa a ser a fonte de verdade de Produto para o projeto.

# 1. Visão do Produto

O **InoClear AI** é uma plataforma multiagente de apoio à gestão de pessoas, criada para apoiar líderes, colaboradores e RH na preparação, condução, registro e acompanhamento de reuniões **1:1**, feedbacks e planos de desenvolvimento.

A solução não substitui a liderança humana. Seu papel é:

- Melhorar a qualidade das conversas entre líderes e liderados;
- Aumentar a frequência das 1:1s;
- Padronizar registros;
- Criar inteligência organizacional para o RH;
- Apoiar o desenvolvimento de lideranças;
- Detectar sinais precoces de desengajamento e riscos organizacionais.

---

# 2. Problema de Negócio

A Clear IT enfrenta dificuldades relacionadas à gestão de pessoas:

- Reuniões 1:1 realizadas de forma inconsistente;
- Baixa padronização de feedbacks;
- Registros descentralizados ou inexistentes;
- Dificuldade do RH em acompanhar a saúde das lideranças;
- Falta de indicadores sobre frequência e qualidade das conversas;
- Pouca visibilidade sobre riscos de desligamento e desengajamento;
- Baixa maturidade de parte das lideranças na condução de conversas difíceis.

---

# 3. Objetivos Estratégicos

## Objetivos de Negócio
- Aumentar a frequência das reuniões 1:1;
- Melhorar a qualidade dos feedbacks;
- Apoiar líderes com pouca experiência em gestão;
- Padronizar registros;
- Gerar indicadores para RH;
- Detectar riscos de desengajamento;
- Melhorar índices de eNPS;
- Melhorar índices de Liderança e Confiança;
- Desenvolver competências do Framework de Levels.

## Objetivos do Produto
- Reduzir esforço operacional do líder;
- Tornar o valor percebido maior que o esforço de uso;
- Criar uma ferramenta de baixa barreira de entrada;
- Disponibilizar acesso via browser em desktop e mobile;
- Centralizar informações de gestão de pessoas.

---

# 4. Personas

## Persona 1 — Coordenador Recém-Promovido
- Alta prioridade.
- Possui pouca experiência em gestão de pessoas.
- Dificuldade em conduzir conversas difíceis.
- Necessita de orientação estruturada.

## Persona 2 — Gestor Intermediário Resistente
- Resistência a processos de RH.
- Falta de tempo.
- Alto impacto organizacional caso não utilize a solução.

## Persona 3 — Líder Engajado
- Já acredita no processo.
- Busca organização, consistência e economia de tempo.

## Persona 4 — Colaborador
- Busca desenvolvimento profissional.
- Deseja acompanhamento constante.
- Precisa de feedbacks mais frequentes.

## Persona 5 — RH
- Necessita de indicadores.
- Precisa atuar de forma preventiva.
- Busca dados centralizados e confiáveis.

---

# 5. Estrutura de Negócio das Conversas

## Reunião 1:1

A reunião 1:1 é:

- Recorrente;
- Estruturada;
- Bilateral;
- Pertence ao liderado;
- Focada em relacionamento e desenvolvimento contínuo.

### Estrutura obrigatória

1. Check-in humano;
2. Pauta do liderado;
3. Status de entregas e obstáculos;
4. Desenvolvimento, carreira e feedback;
5. Acordos e próximos passos.

### Temas obrigatórios
- Bem-estar;
- Energia do colaborador;
- Obstáculos;
- Desenvolvimento;
- Revisão de acordos;
- Novos combinados.

---

## Sessão de Feedback

Conversa focada em comportamento específico.

Pode assumir quatro formatos:

- Reconhecimento;
- Desenvolvimento;
- Corretivo urgente;
- Feedback dentro da 1:1.

### Estrutura obrigatória

1. Contexto e intenção;
2. Escuta ativa;
3. Modelo SBI;
4. Acordos e próximos passos.

---

# 6. Regras de Frequência

## Reuniões 1:1
- Quinzenal ou mensal.

## Feedbacks
- Novos colaboradores: 45 e 90 dias;
- Colaboradores em risco: quinzenal;
- Feedback corretivo: até 48 horas após o evento;
- Reconhecimento e desenvolvimento: bimestral ou trimestral.

---

# 7. PDI — Plano de Desenvolvimento Individual

O PDI deverá ser:

- Simples;
- Acionável;
- Conectado ao Framework de Levels.

## Estrutura

### Competência e Objetivo
Competência do framework e comportamento esperado.

### Ações Concretas
Máximo de três ações verificáveis.

### Prazo e Evidências
Definição de marcos de acompanhamento.

### Suporte do Gestor
Ações de apoio fornecidas pela liderança.

---

# 8. Arquitetura de Valor

## Agente 1 — Iniciador
Responsável pelo planejamento das reuniões.

Funcionalidades:
- Lembretes;
- Geração de pauta;
- Recomendações de perguntas;
- Identificação de pendências;
- Preparação personalizada.

---

## Agente 2 — Facilitador
Responsável pela condução assistida.

Funcionalidades:
- Geração de roteiros;
- Apoio em feedbacks difíceis;
- Sugestão de perguntas;
- Criação de planos de ação;
- Sugestões de PDI.

---

## Agente 3 — Verificador
Responsável pelo acompanhamento de compromissos.

Funcionalidades:
- Controle de frequência;
- Monitoramento de evolução;
- Acompanhamento de PDIs;
- Alertas de ausência de reuniões;
- Monitoramento de reincidências.

---

## Agente 4 — Analista
Responsável pela inteligência organizacional.

Funcionalidades:
- Análise de sentimento;
- Detecção de riscos;
- Identificação de padrões;
- Monitoramento da saúde organizacional;
- Apoio preventivo ao RH.

---

# 9. Fluxo de Negócio

1. Identificar a proximidade da reunião;
2. Gerar pauta personalizada;
3. Apoiar a condução;
4. Registrar automaticamente a conversa;
5. Monitorar compromissos;
6. Consolidar dados;
7. Entregar inteligência ao RH.

---

# 10. Portais

## Portal do Líder
- Próximas reuniões;
- Histórico do colaborador;
- Pautas sugeridas;
- Resumos gerados pela IA;
- Ações pendentes;
- Evolução de PDIs;
- Histórico de feedbacks.

## Portal do Colaborador
- Histórico de feedbacks;
- Objetivos acordados;
- Desenvolvimento;
- Metas;
- Próximas reuniões.

## Portal do RH
- Dashboard estratégico;
- Indicadores;
- Alertas;
- Riscos organizacionais;
- Exportação de dados.

---

# 11. Dados e Indicadores para RH

## Indicadores obrigatórios
- Frequência de 1:1 por líder;
- Ranking de cadência;
- Colaboradores sem 1:1 há mais de 30 dias;
- Taxa de geração de PDI;
- Sinalizações de risco;
- Temas mais recorrentes;
- Competências mais trabalhadas;
- Perfil de maturidade das lideranças.

## Classificação de maturidade
- Iniciante;
- Em desenvolvimento;
- Consistente;
- Referência.

---

# 12. Integrações Futuras

- Microsoft Teams;
- Solides;
- Power BI;
- Exportação CSV;
- Exportação Excel;
- Exportação PDF.

---

# 13. Regras de Registro

## Informações que devem ser registradas
- Data;
- Duração;
- Temas abordados;
- Feedbacks no modelo SBI;
- Acordos;
- Evolução de acordos;
- Próxima reunião;
- Sinalizações ao RH.

## Informações que NÃO devem ser registradas
- Dados médicos;
- Dados familiares;
- Informações pessoais sensíveis;
- Opiniões sobre terceiros;
- Julgamentos de caráter.

---

# 14. Compliance e LGPD

- IA não substitui o líder;
- Decisão humana final;
- Dados anonimizados para análises;
- Não solicitar CPF, matrícula ou salário;
- Não solicitar informações de saúde;
- Não solicitar dados familiares;
- Não gerar conteúdo discriminatório;
- Não configurar assédio;
- Não transferir responsabilidade das decisões para a IA.

---

# 15. KPIs do Produto

- Frequência de reuniões;
- Evolução dos PDIs;
- Risco organizacional;
- Clima organizacional;
- eNPS;
- Índice de Liderança e Confiança;
- Taxa de adesão dos líderes;
- Percentual de 1:1 com bloco de desenvolvimento;
- Taxa de conclusão de acordos;
- Quantidade de riscos identificados preventivamente.

---

# 16. Backlog Estratégico Inicial

| ID | Épico | Objetivo |
|----|--------|-----------|
| EP-01 | Gestão de 1:1 | Estruturar e registrar reuniões |
| EP-02 | Gestão de Feedbacks | Melhorar qualidade das conversas |
| EP-03 | Gestão de PDIs | Desenvolver colaboradores |
| EP-04 | Analytics RH | Gerar inteligência organizacional |
| EP-05 | Alertas e Riscos | Atuação preventiva do RH |
| EP-06 | Desenvolvimento de Lideranças | Aumentar maturidade gerencial |

---

# 17. MVP

## Escopo Inicial
- Liberação para toda a liderança da empresa;
- Acesso web responsivo;
- Registro centralizado;
- Dashboards básicos;
- Alertas de frequência;
- Geração de pautas;
- Geração de resumos.

## Critérios de Sucesso
- Aumento da frequência de 1:1;
- Aumento da adesão das lideranças;
- Melhor percepção de valor pelo RH;
- Geração de indicadores confiáveis;
- Melhoria nos índices de clima e liderança.

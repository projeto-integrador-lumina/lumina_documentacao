
# Declaração Estratégica — Sprint Final do Lumina

## 1. Contextualização

O Lumina é um projeto de desenvolvimento de uma solução tecnológica de apoio à terapia fonoaudiológica infantil, voltada a crianças de 4 a 12 anos com desvio fonológico.

O sistema é composto por um Dashboard web destinado aos fonoaudiólogos, uma aplicação infantil com recursos de gamificação e um backend responsável pela comunicação e pelo gerenciamento dos dados.

A Sprint Final foi planejada a partir das análises SWOT e TOWS e da priorização MoSCoW, considerando o estágio atual do desenvolvimento, os recursos disponíveis e os riscos relacionados à apresentação final.

## 2. Objetivo da Sprint Final

Garantir a estabilidade das funcionalidades implementadas, validar a integração entre os componentes do sistema e preparar uma demonstração funcional do Lumina para a banca avaliadora.

A Sprint Final prioriza a qualidade e a confiabilidade da entrega existente, evitando a inclusão de funcionalidades complexas que possam comprometer o prazo ou a estabilidade do sistema.

## 3. Escopo da Entrega

### 3.1 Funcionalidades que serão demonstradas

**Dashboard web:**

- Login e autenticação de usuários.
- Cadastro e gerenciamento de pacientes.
- Cadastro e gerenciamento de usuários.
- Consulta, edição e exclusão de registros.
- Demais funcionalidades implementadas e validadas antes da apresentação.

**Aplicação infantil:**

- Execução da aplicação diretamente pelo navegador.
- Navegação entre as telas implementadas.
- Demonstração das atividades e dos recursos de gamificação que estiverem funcionais.
- Integração com o backend nas funcionalidades disponíveis.

A apresentação será realizada com o sistema em execução, utilizando dados fictícios para evitar a exposição de informações pessoais ou sensíveis.

### 3.2 Funcionalidades fora do escopo

A equipe definiu que as seguintes atividades não serão realizadas durante a Sprint Final:

- Conversão do aplicativo infantil em PWA instalável.
- Implementação de novas funcionalidades complexas.
- Expansão da solução para outros públicos e alterações de fala.
- Validação clínica com crianças.

Essas decisões foram estabelecidas com base na priorização MoSCoW, considerando as limitações de tempo, recursos e a necessidade de garantir uma entrega funcional.

## 4. Estratégias Adotadas

Com base na matriz TOWS, foram definidas as seguintes estratégias:

### FO — Forças e Oportunidades

Aproveitar as funcionalidades implementadas no Dashboard e os recursos da aplicação infantil para demonstrar o potencial da solução no apoio à terapia fonoaudiológica e à prática domiciliar.

### FA — Forças e Ameaças

Priorizar a estabilidade do sistema, a proteção dos dados e a validação das funcionalidades essenciais, reduzindo os riscos técnicos durante a apresentação.

### DO — Fraquezas e Oportunidades

Concentrar os esforços da equipe na validação dos recursos existentes, considerando as limitações de tempo e a ausência de testes com usuários reais.

### DA — Fraquezas e Ameaças

Restringir o escopo da Sprint Final, evitar novas funcionalidades complexas e preparar alternativas técnicas para possíveis falhas durante a demonstração.

## 5. Priorização das Atividades

As atividades foram classificadas conforme o método MoSCoW:

| Prioridade | Direcionamento |
|---|---|
| Must Have | Validação das funcionalidades principais, integração entre os componentes, correção de falhas críticas e preparação da demonstração. |
| Should Have | Atualização da documentação e melhorias secundárias. |
| Could Have | Ajustes visuais, responsividade e ampliação de testes, caso exista tempo disponível. |
| Won't Have | Conversão para PWA instalável e implementação de novas funcionalidades complexas. |

As tarefas foram organizadas em Issues, vinculadas às Milestones da Sprint Final e acompanhadas pelo GitHub Projects.

## 6. Plano de Contingência

Para reduzir os riscos de indisponibilidade da infraestrutura durante a banca, será preparado um ambiente local de contingência.

Esse ambiente será composto por:

- Dashboard web executado localmente.
- Aplicação infantil acessível pelo navegador.
- Backend Node.js executado localmente.
- MongoDB Community Server como banco de dados local.
- MongoDB Compass para gerenciamento e visualização dos dados.

Caso ocorra indisponibilidade da internet ou do MongoDB Atlas, a equipe poderá utilizar o ambiente local previamente configurado e validado.

A demonstração continuará sendo realizada em tempo real, sem substituição por vídeos gravados.

O MongoDB Atlas permanecerá como banco de dados principal do projeto. O banco local será utilizado exclusivamente como alternativa de contingência.

A equipe também verificará antecipadamente eventuais dependências de serviços externos que possam limitar o funcionamento offline.

## 7. Organização e Acompanhamento

O planejamento da Sprint Final será acompanhado pelo GitHub Projects da organização Lumina.

As atividades estão distribuídas entre os seguintes estados:

- Backlog: atividades futuras ou fora do escopo da Sprint Final.
- Ready (DoR): tarefas definidas e prontas para execução.
- In Progress: atividades em desenvolvimento ou validação.
- In Review: tarefas aguardando revisão.
- Done (DoD): atividades concluídas e validadas.

Cada Issue possui uma prioridade MoSCoW e, quando aplicável, um responsável e uma Milestone.

O prazo interno estabelecido para a conclusão das atividades é 15 de novembro de 2026, considerando que o período das bancas ocorrerá entre 16 e 27 de novembro de 2026.

## 8. Critérios de Sucesso

A Sprint Final será considerada satisfatória quando:

- As funcionalidades essenciais selecionadas estiverem funcionando corretamente.
- A integração entre os componentes estiver validada.
- As falhas críticas que comprometam a demonstração tiverem sido corrigidas.
- O ambiente local de contingência estiver preparado e testado.
- A documentação representar corretamente o estado do projeto.
- A equipe estiver preparada para demonstrar o sistema e explicar suas limitações.

## 9. Conclusão

A estratégia definida para a Sprint Final do Lumina busca garantir uma entrega funcional e coerente com o estágio atual de desenvolvimento.

A equipe optou por priorizar a estabilidade, a validação e a preparação da demonstração, em vez de ampliar o escopo com funcionalidades que não poderiam ser implementadas e testadas adequadamente no tempo disponível.

As análises SWOT e TOWS, juntamente com a priorização MoSCoW, fundamentaram essas decisões e orientaram a organização das atividades no GitHub.

## 10. Referências do Projeto

- [Organização Lumina](https://github.com/projeto-integrador-lumina)
- [Repositório de documentação](https://github.com/projeto-integrador-lumina/lumina_documentacao)
- [GitHub Projects](https://github.com/orgs/projeto-integrador-lumina/projects/1)

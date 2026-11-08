
# Matriz TOWS — Projeto Lumina

## 1. Introdução

A matriz TOWS é uma ferramenta de planejamento estratégico que utiliza os fatores identificados na análise SWOT para definir ações e estratégias.

Enquanto a SWOT permite identificar forças, fraquezas, oportunidades e ameaças, a TOWS estabelece relações entre esses fatores, orientando a tomada de decisões.

No projeto **Lumina**, a matriz TOWS será utilizada para definir estratégias para a Sprint Final, considerando as limitações da equipe, as funcionalidades desenvolvidas e os riscos relacionados à entrega.

A análise considera o estado atual do sistema, composto por um Dashboard web para fonoaudiólogos, um backend compartilhado e uma aplicação infantil acessível pelo navegador.

## 2. Matriz TOWS

| Estratégias | Oportunidades (O) | Ameaças (T) |
|---|---|---|
| **Forças (S)** | **FO — Estratégias Ofensivas:** aproveitar a interface infantil, a gamificação e as funcionalidades do Dashboard para demonstrar o potencial da solução no acompanhamento terapêutico e na prática domiciliar. | **FA — Estratégias de Confronto:** utilizar as funcionalidades já desenvolvidas para priorizar a estabilidade da aplicação, a proteção dos dados e a confiabilidade da demonstração, considerando os riscos de segurança e acessibilidade. |
| **Fraquezas (W)** | **DO — Estratégias de Reforço:** concentrar os esforços da equipe na validação das funcionalidades existentes e na integração entre os componentes, aproveitando o potencial da solução para o atendimento remoto. | **DA — Estratégias Defensivas:** limitar o escopo da Sprint Final, evitar funcionalidades complexas sem tempo adequado para testes e preparar alternativas para eventuais falhas durante a apresentação. |

## 3. Estratégias Definidas

### 3.1 Estratégia FO — Forças e Oportunidades

**Objetivo:** aproveitar os diferenciais do Lumina para demonstrar sua proposta de valor.

**Fatores relacionados:**
- Forças: gamificação, interface infantil e interativa, acompanhamento remoto e personalização das atividades.
- Oportunidades: crescimento da saúde digital, necessidade de prática terapêutica domiciliar e integração entre jogo, painel e comunicação.

**Ações propostas:**
- Demonstrar as principais funcionalidades implementadas no Dashboard.
- Apresentar as funcionalidades disponíveis no aplicativo infantil executado pelo navegador.
- Evidenciar como a solução foi planejada para apoiar o acompanhamento fonoaudiológico.
- Destacar os diferenciais do projeto, distinguindo funcionalidades implementadas das previstas.

### 3.2 Estratégia FA — Forças e Ameaças

**Objetivo:** utilizar os recursos existentes para reduzir riscos técnicos e operacionais.

**Fatores relacionados:**
- Forças: acompanhamento remoto, interface infantil e personalização das atividades.
- Ameaças: LGPD, vulnerabilidades de segurança e desigualdade de acesso à internet e dispositivos.

**Ações propostas:**
- Verificar a autenticação e o controle de acesso às funcionalidades do Dashboard.
- Utilizar dados fictícios durante a demonstração, evitando exposição de informações pessoais ou sensíveis.
- Testar o funcionamento das aplicações nos navegadores utilizados na apresentação.
- Verificar a estabilidade da comunicação com o backend e o banco de dados.

### 3.3 Estratégia DO — Fraquezas e Oportunidades

**Objetivo:** reduzir limitações internas e aproveitar as possibilidades de aplicação da solução.

**Fatores relacionados:**
- Fraquezas: equipe pequena, tempo e orçamento limitados, ausência de testes com usuários reais e testes automatizados insuficientes.
- Oportunidades: crescimento do atendimento remoto, necessidade de prática em casa e possíveis parcerias com clínicas.

**Ações propostas:**
- Priorizar testes manuais das funcionalidades essenciais.
- Validar os fluxos de cadastro, consulta, edição e exclusão de pacientes e usuários.
- Verificar as funcionalidades disponíveis no aplicativo infantil.
- Registrar limitações e funcionalidades que ainda necessitam de validação.
- Organizar a documentação para facilitar futuras melhorias e avaliações com profissionais.

### 3.4 Estratégia DA — Fraquezas e Ameaças

**Objetivo:** minimizar os riscos da entrega final, considerando as limitações de desenvolvimento.

**Fatores relacionados:**
- Fraquezas: equipe pequena, tempo limitado e testes insuficientes.
- Ameaças: vulnerabilidades de segurança, problemas de acesso à internet e perda de interesse dos usuários.

**Ações propostas:**
- Evitar a inclusão de novas funcionalidades complexas na Sprint Final.
- Manter a aplicação infantil acessível pelo navegador, deixando a conversão para PWA para uma etapa futura.
- Priorizar a correção de falhas que comprometam as funcionalidades essenciais.
- Preparar um plano de contingência para a demonstração.
- Documentar funcionalidades não concluídas e limitações conhecidas.


## 4. Plano de Contingência

Para reduzir os riscos durante a apresentação final do Lumina, foram definidas medidas de contingência que permitam demonstrar as funcionalidades do sistema em tempo real, mesmo diante de possíveis falhas na infraestrutura principal.

| Risco | Plano de Contingência |
|---|---|
| Falha de conexão com a internet | Executar o Dashboard, o aplicativo infantil e o backend localmente, utilizando um banco MongoDB instalado na máquina. |
| Indisponibilidade do MongoDB Atlas | Alterar a configuração de conexão do backend para o MongoDB Community Server local, com os dados previamente preparados e gerenciados pelo MongoDB Compass. |
| Indisponibilidade do backend hospedado | Executar o servidor Node.js localmente, mantendo a comunicação com o Dashboard e o aplicativo infantil. |
| Erro em alguma funcionalidade | Priorizar a demonstração dos fluxos previamente testados e apresentar as limitações identificadas. |
| Problemas de acesso ao aplicativo infantil | Executar a aplicação diretamente no navegador, utilizando o ambiente local previamente configurado. |
| Tempo insuficiente para concluir melhorias | Priorizar a estabilidade das funcionalidades essenciais e registrar as demais como atividades futuras. |

### 4.1 Ambiente Local de Contingência

Como alternativa à infraestrutura principal, será preparado um ambiente de execução local, composto por:

- Dashboard web executado localmente.
- Aplicativo infantil acessado pelo navegador.
- Backend Node.js executado localmente.
- MongoDB Community Server instalado na máquina.
- MongoDB Compass para gerenciamento e visualização dos dados.

O ambiente utilizará dados fictícios previamente cadastrados, evitando a exposição de informações pessoais ou sensíveis.

Antes da apresentação, serão realizados testes para verificar o funcionamento dos principais fluxos do sistema, garantindo que a demonstração possa ocorrer em tempo real, sem depender da disponibilidade do MongoDB Atlas.

A utilização do ambiente local será uma medida de contingência, sem substituir a arquitetura principal do projeto, que continuará utilizando o MongoDB Atlas.

## 5. Direcionamento para a Sprint Final

Com base nas estratégias estabelecidas, a Sprint Final do Lumina terá como foco a estabilização, a validação e a preparação das funcionalidades já desenvolvidas.

As prioridades serão:

1. Validar as funcionalidades principais do Dashboard.
2. Verificar a integração entre Dashboard, backend e banco de dados.
3. Testar as funcionalidades disponíveis no aplicativo infantil.
4. Corrigir falhas críticas identificadas durante os testes.
5. Atualizar a documentação com o estado real do projeto.
6. Preparar o ambiente e o roteiro da demonstração final.

A conversão da aplicação infantil para PWA instalável não será priorizada nesta Sprint, considerando as limitações de tempo e a necessidade de garantir uma entrega funcional.

## 6. Conclusão

A matriz TOWS permitiu transformar os fatores identificados na análise SWOT em estratégias direcionadas à Sprint Final do Lumina.

As decisões priorizam a estabilidade, a validação das funcionalidades existentes e a redução dos riscos da apresentação, respeitando os recursos e o tempo disponíveis.

As estratégias servirão como referência para a classificação das atividades pelo método MoSCoW e para a organização das Issues no GitHub Projects.

## 7. Documentos Relacionados

- [Organização Lumina](https://github.com/projeto-integrador-lumina)
- [Documentação do projeto](https://github.com/projeto-integrador-lumina/lumina_documentacao)
- [GitHub Projects](https://github.com/orgs/projeto-integrador-lumina/projects/1)

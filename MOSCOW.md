
# Priorização MoSCoW — Sprint Final do Lumina

## 1. Introdução

A técnica MoSCoW é utilizada para classificar requisitos e atividades de acordo com sua importância para a entrega de um projeto.

No Lumina, a priorização foi definida com base nas análises SWOT e TOWS, considerando o estágio atual de desenvolvimento, as limitações da equipe e os riscos da apresentação final.

O objetivo da Sprint Final é garantir a estabilidade das funcionalidades implementadas, validar os principais fluxos e preparar um ambiente confiável para a demonstração do sistema.

## 2. Classificação MoSCoW

### 2.1 Must Have — Obrigatório

Atividades essenciais para garantir uma demonstração funcional e confiável do Lumina.

| Atividade | Justificativa |
|---|---|
| Validar as operações de cadastro, consulta, edição e exclusão de pacientes e usuários | Garantir o funcionamento das principais funcionalidades do Dashboard. |
| Validar autenticação e controle de acesso | Garantir que o acesso ao sistema funcione corretamente. |
| Testar a integração entre as aplicações e o backend | Verificar a comunicação entre os componentes do sistema. |
| Validar as funcionalidades implementadas no aplicativo infantil | Garantir que os recursos disponíveis possam ser demonstrados no navegador. |
| Corrigir falhas críticas identificadas | Evitar erros que comprometam a demonstração. |
| Preparar e testar o ambiente local de contingência | Permitir a demonstração em tempo real, mesmo sem acesso ao MongoDB Atlas. |
| Preparar o roteiro da apresentação | Organizar a sequência de demonstração das funcionalidades. |

### 2.2 Should Have — Importante

Atividades que contribuem para a qualidade da entrega, mas cuja ausência não impede a demonstração das funcionalidades essenciais.

| Atividade | Justificativa |
|---|---|
| Atualizar a documentação técnica | Registrar a situação atual do sistema e as limitações existentes. |
| Revisar mensagens de erro e orientações ao usuário | Melhorar a compreensão e a usabilidade das aplicações. |
| Revisar funcionalidades secundárias | Identificar e corrigir problemas que não comprometam os fluxos principais. |

### 2.3 Could Have — Desejável

Melhorias que poderão ser realizadas caso exista tempo disponível após a conclusão das atividades prioritárias.

| Atividade | Justificativa |
|---|---|
| Realizar ajustes visuais e de responsividade | Melhorar a apresentação e a experiência de uso. |
| Ampliar a cobertura de testes automatizados | Aumentar a confiabilidade do sistema em futuras evoluções. |
| Aprimorar detalhes de interface do aplicativo infantil | Tornar a experiência mais agradável sem alterar o escopo principal. |

### 2.4 Won't Have — Fora do Escopo da Sprint Final

Atividades que não serão realizadas nesta Sprint, mas poderão ser consideradas em etapas futuras.

| Atividade | Justificativa |
|---|---|
| Converter o aplicativo infantil em PWA instalável | A aplicação permanecerá acessível pelo navegador, priorizando a estabilidade das funcionalidades existentes. |
| Implementar novas funcionalidades complexas | Evitar aumento de escopo e riscos próximos à entrega. |
| Expandir a solução para outros públicos e alterações de fala | A expansão depende de planejamento, desenvolvimento e validação adicionais. |
| Realizar validação clínica com crianças | Exige planejamento específico, participação de profissionais e procedimentos éticos adequados. |

## 3. Critérios de Priorização

A classificação das atividades considerou:

- Impacto no funcionamento das funcionalidades principais.
- Risco de falhas durante a apresentação.
- Tempo disponível para a Sprint Final.
- Capacidade de desenvolvimento da equipe.
- Dependências técnicas entre as aplicações.
- Estratégias definidas na matriz TOWS.

## 4. Organização da Sprint Final

As atividades classificadas como Must Have serão priorizadas no GitHub Projects.

As atividades Should Have serão executadas conforme a disponibilidade da equipe, após a garantia das funcionalidades essenciais.

As atividades Could Have serão consideradas apenas se não comprometerem as prioridades anteriores.

As atividades Won't Have serão registradas como fora do escopo da Sprint Final, mantendo a rastreabilidade das decisões.

Cada atividade selecionada para execução deverá possuir uma Issue no GitHub, com descrição, prioridade, responsável e critérios de aceitação.

## 5. Conclusão

A priorização MoSCoW permitiu estabelecer um escopo realista para a Sprint Final do Lumina.

O planejamento concentra os esforços na validação das funcionalidades existentes, na correção de falhas críticas e na preparação de um ambiente local de contingência.

Dessa forma, busca-se reduzir os riscos técnicos da apresentação e garantir uma demonstração funcional, respeitando as limitações de tempo e recursos da equipe.

## 6. Documentos Relacionados

- [Organização Lumina](https://github.com/projeto-integrador-lumina)
- [Repositório de documentação](https://github.com/projeto-integrador-lumina/lumina_documentacao)
- [GitHub Projects](https://github.com/orgs/projeto-integrador-lumina/projects/1)

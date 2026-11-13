# 📚 Unidade 3 - Atividade Prática — Engenharia de Requisitos

**Estudo de Caso:** Sistema de Atendimento e Agendamento de uma Clínica  
**Projeto:** Clínica Vida+ Saúde  
**Disciplina:** Engenharia de Requisitos  
**Curso:** Engenharia de Software  

---

## 📑 Sumário

1. [Identificação do Grupo](#-identificação-do-grupo)
2. [Identificação do Processo](#-6-etapa-1--identificação-do-processo)
3. [Identificação dos Stakeholders](#-7-etapa-2--identificação-dos-stakeholders)
4. [Análise do Processo Atual](#8-etapa-3--análise-do-processo-atual)
5. [Identificação das Atividades](#️-9-etapa-4--identificação-das-atividades)
6. [Requisitos Funcionais](#requisitos-funcionais)
7. [Requisitos Não Funcionais](#requisitos-não-funcionais)
8. [Regras de Negócio](#-10-etapa-5--regras-de-negócio)
9. [Identificação dos Problemas](#-11-etapa-6--identificação-dos-problemas)
10. [Modelagem AS-IS](#-12-etapa-7--modelagem-as-is)
11. [Proposta de Melhorias](#-13-etapa-8--proposta-de-melhorias)

---

## 👥 Identificação do Grupo

| Papel | Responsabilidade | Nome |
|---|---|---|
| Analista de Requisitos | Levantar e documentar os requisitos | Elton |
| Analista de Processos | Analisar o processo de negócio | Gabriel |
| Representante do Cliente | Representar as necessidades dos pacientes | Danilo |
| Representante da Organização | Representar os interesses da clínica | |
| Modelador | Elaborar os modelos dos processos | Rafael |
| Relator | Organizar e documentar o trabalho | Augusto |

---

## 🔎 6. Etapa 1 – Identificação do Processo

**1. Qual é o nome do processo?**

R: Processo de Atendimento e Agendamento de Consultas Médicas

**2. Qual é o objetivo do processo?**

R: ​Reduzir o processo de atendimento fragmentado da Clínica Vida+ Saúde

**3. Quem é o cliente do processo?**

R: Pacientes; Funcionários Administrativos;

**4. Quem executa as atividades?**

R: Funcionários Administrativos.

**5. Quem gerencia o processo?**

R: A clínica.

**6. Qual evento inicia o processo?**

R: Quando paciente decide agendar uma consulta.

**7. Qual evento encerra o processo?**

R: Consulta agendada, confirmada, cancelada ou realizada.

**8. Qual valor é entregue ao cliente?**

R: Facilita a marcação e realização da consulta

---

## 👤 7. Etapa 2 – Identificação dos Stakeholders

| Stakeholder | Interesse no processo | Participação | Necessidades |
|---|---|---|---|
| Paciente | Agendar consultas com facilidade, sem erros de horário ou repetição de dados. | Solicitar agendamento presencialmente ou online. | cadastro único e definitivo. Agilidade no atendimento. Lembretes automáticos. |
| Recepcionista | Agendar sem conflito de horários e eliminar o retrabalho de planilhas. | Atende clientes, consulta agendas, cadastrar e confirmar consultas. | Agenda centralizada em tempo real. Busca rápida de cadastros. Gestão simples de remarcações. |
| Médico | Ter uma agenda organizada e atender os pacientes no horário | Realiza as consultas e registra os atendimentos | Agenda sem horários duplicados. Acesso rápido ao histórico do paciente. |
| Gerente | Acompanhar a melhorar o funcionamento da clínica. | Acompanha a agenda e os resultados do atendimento. | Ter Controle do processo e acesso aos indicadores. |
| Direção | Melhorar o atendimento e reduzir problemas na clínica. | Toma decisões e acompanha os resultados. | Indicadores, organização e redução de custos e erros. |
| Equipe de TI | Garantir que o sistema funcione corretamente. | Desenvolve, mantém e dá suporte ao sistema. | Informações claras, segurança dos dados e facilidade de manutenção. |

---

## 8. Etapa 3 – Análise do Processo Atual

### Quem?

**Quem é o cliente?**

O cliente é o paciente que procura a clínica para marcar uma consulta.

**Quem executa as atividades?**

A recepcionista faz os agendamentos, cadastros, confirmações e cancelamentos. O médico realiza a consulta e registra o atendimento.

**Quem gerencia?**

A direção e os responsáveis pela clínica.

**Quem fornece informações?**

O paciente fornece seus dados e o médico informa sua disponibilidade.

**Quem participa das decisões?**

A recepção, os médicos e a gestão da clínica.

### O quê?

**Entradas:** dados do paciente, pedido de consulta e horários dos médicos.

**Saídas:** consulta agendada, confirmada, cancelada ou realizada.

**Recursos:** computadores, celulares, internet e funcionários.

**Ferramentas:** planilhas, WhatsApp, telefone e sistema usado pelo médico.

**Problemas:** conflitos de horários, informações desatualizadas, retrabalho, cadastro repetido e falhas na comunicação.

**Pontos positivos:** a clínica possui diferentes formas de contato com o paciente e uma equipe responsável pelos atendimentos.

**Indicadores:** consultas realizadas, cancelamentos, faltas, remarcações e ocupação dos horários.

### Quando?

**Início:** quando o paciente entra em contato para marcar uma consulta.

**Execução:** durante o agendamento e no horário marcado para a consulta.

**Fim:** quando a consulta é realizada ou cancelada.

### Onde?

**Início:** telefone, WhatsApp ou recepção.

**Atividades:** principalmente na recepção e nos consultórios.

**Registro:** os agendamentos ficam em planilhas e o atendimento médico em outro sistema.

### Por quê?

**Por que existe?**

Para organizar as consultas e os horários dos médicos.

**Valor para o paciente:** facilita a marcação e realização da consulta.

**Valor para a clínica:** ajuda a organizar os médicos, pacientes e horários.

### Como?

A clínica contará com um sistema web para realizar e gerenciar os agendamentos dos pacientes de forma centralizada. A equipe poderá acessar o sistema por meio de login, sendo que usuários com perfil de administrador, como recepcionistas, terão acesso a funcionalidades adicionais para realizar as operações necessárias no gerenciamento da clínica.

Por meio do sistema, a recepcionista poderá consultar a disponibilidade dos profissionais, realizar novos agendamentos, confirmar, cancelar ou remarcar consultas, além de visualizar e organizar a agenda dos médicos. Dessa forma, todas as informações ficarão centralizadas e atualizadas no sistema, reduzindo o risco de conflitos de horários e erros causados pelo uso de planilhas.

Caso ocorra alguma alteração na agenda de um médico, como mudança de horário ou cancelamento de atendimento, a equipe responsável poderá atualizar as informações diretamente no sistema, permitindo um melhor controle dos compromissos e facilitando a comunicação com os pacientes.

O sistema também terá diferentes níveis de acesso, permitindo que cada usuário tenha acesso apenas às funcionalidades correspondentes ao seu perfil. Usuários administradores, como recepcionistas, poderão realizar as principais operações de gerenciamento dos agendamentos, enquanto outros usuários poderão ter permissões mais restritas.

---

## ⚙️ 9. Etapa 4 – Identificação das Atividades

| Atividade | Responsável | Entrada | Saída | Regra |
|---|---|---|---|---|
| Solicitar consulta | Paciente | Necessidade de atendimento | solicitação de consulta | O paciente deve informar os dados necessários para solicitar a consulta. |
| Identificar paciente | Recepcionista | Solicitação de consulta | Paciente identificado | paciente deve ter cadastro antes do agendamento |
| Consultar agenda | Recepcionista | Dados do paciente e solicitação da consulta | Agenda do médico | agenda do médico deve ser consultada antes de verificar a disponibilidade |
| Verificar disponibilidade | Recepcionista | Agenda do médico | Horário disponível ou indisponível | Só deve ser marcado a consulta se houver horário vago |
| Registrar agendamento | Recepcionista | Dados do paciente e horário disponível | Consulta agendada | Agendamento deve conter data, horário, paciente e o médico que realizará o atendimento |

---

## Requisitos Funcionais

1. O sistema deve permitir que o paciente solicite uma consulta.
2. O sistema deve permitir localizar o cadastro do paciente por meio de informações como CPF, nome ou telefone, evitando a necessidade de informar novamente seus dados cadastrais.
3. O sistema deve permitir que a recepcionista consulte a agenda dos médicos, visualizando os horários já ocupados e disponíveis.
4. O sistema deve verificar automaticamente se existe horário disponível para o médico ou especialidade solicitada antes de realizar o agendamento.
5. O sistema deve permitir registrar o agendamento, vinculando o paciente ao médico, à data e ao horário escolhido.
6. O sistema deve permitir confirmar o agendamento e enviar uma confirmação ao paciente, preferencialmente por WhatsApp ou outro canal disponível.
7. O sistema deve permitir que o médico acesse os dados necessários do paciente e realize o atendimento agendado.
8. O sistema deve gerar relatórios com o quantitativo de consultas e faltas por período.

## Requisitos Não Funcionais

1. O sistema deve garantir que os dados dos pacientes sejam acessados somente por usuários autorizados.
2. O sistema deve proteger os dados pessoais e informações médicas dos pacientes contra acessos não autorizados.
3. O sistema deve apresentar as informações de agenda e disponibilidade dos médicos rapidamente, evitando atrasos durante o agendamento.
4. O sistema deve garantir que os agendamentos sejam registrados corretamente, evitando conflitos de horários para o mesmo médico.
5. O sistema deve possuir uma interface simples e intuitiva, permitindo que as recepcionistas realizem suas atividades sem dificuldade.
6. O sistema deve estar disponível durante o horário de funcionamento da clínica, permitindo que as recepcionistas realizem os agendamentos.

---

## 📋 10. Etapa 5 – Regras de Negócio

| Código | Regra de Negócio | Origem |
|---|---|---|
| RN01 | O paciente deve possuir cadastro para realizar um agendamento. | Processo da clínica |
| RN02 | Um médico não pode ter dois pacientes no mesmo horário. | Agenda médica |
| RN03 | A consulta só pode ser marcada em um horário disponível. | Agenda médica |
| RN04 | O cancelamento deve liberar o horário do médico. | Processo de agendamento |
| RN05 | Os dados do paciente devem ser conferidos antes do agendamento. | Recepção |
| RN06 | Alterações na agenda do médico devem ser informadas aos pacientes afetados. | Gestão da clínica |
| RN07 | O agendamento deve conter data, horário, paciente e médico. | Processo de agendamento |
| RN08 | O atendimento deve ser registrado após a consulta. | Médico |
| RN09 | Uma consulta cancelada pode ser remarcada para outro horário disponível. | Recepção |
| RN10 | Cada usuário deve acessar somente as funções permitidas pelo seu perfil. | Gestão/TI |

---

## 🚨 11. Etapa 6 – Identificação dos Problemas

| Problema | Causa provável | Impacto | Prioridade |
|---|---|---|---|
| Conflito de horários | Uso de planilhas diferentes | Agendamentos duplicados | 🔴 Alta |
| Retrabalho | Informações espalhadas | Perda de tempo | 🔴 Alta |
| Cadastro repetido | Falta de cadastro centralizado | Demora no atendimento | 🟡 Média |
| Informações desatualizadas | Planilhas não atualizadas ao mesmo tempo | Erros nos agendamentos | 🔴 Alta |
| Falta de lembretes | Processo feito manualmente | Aumento das faltas | 🟡 Média |
| Cancelamentos manuais | Falta de controle centralizado | Dificuldade para liberar horários | 🟡 Média |
| Alteração da agenda do médico | Comunicação individual | Retrabalho da recepção | 🔴 Alta |
| Falha na confirmação | WhatsApp e planilha separados | Paciente pode ficar sem atendimento | 🔴 Alta |

---

## 🔄 12. Etapa 7 – Modelagem AS-IS

Elabore o fluxograma do processo atual (AS-IS).

O modelo deve representar:

- início;
- atividades;
- responsáveis;
- decisões;
- caminhos alternativos;
- regras;
- entradas;
- saídas;
- fim do processo.

---

## 🔧 13. Etapa 8 – Proposta de Melhorias

| Problema | Melhoria proposta | Benefício esperado |
|---|---|---|
| Conflito de horários | Agenda centralizada | Redução de conflitos e agendamentos duplicados |
| Cadastro duplicado | Cadastro único de pacientes | Redução de retrabalho e maior organização das informações |
| Falta de lembretes | Envio automático de lembretes | Redução de faltas e maior pontualidade dos pacientes |
| Cancelamentos feitos manualmente | Cancelamento e remarcação pelo sistema | Maior agilidade e atualização automática da agenda |
| Alterações na agenda do médico | Atualização da agenda em tempo real | Evita informações desatualizadas e reduz erros |
| Controle de acesso limitado | Login com diferentes níveis de permissão | Maior segurança das informações e controle das operações |
| Dificuldade para consultar horários | Visualização dos horários disponíveis no sistema | Agendamentos mais rápidos e facilidade para encontrar horários |
| Comunicação de alterações aos pacientes | Notificações automáticas | Melhoria na comunicação e redução de esquecimentos e desencontros |

---

⭐ **Projeto desenvolvido para fins acadêmicos — Engenharia de Requisitos.**

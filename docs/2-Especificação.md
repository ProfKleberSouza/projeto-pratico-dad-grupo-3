# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas
> **Membros da Comunidade** com idade entre 20 e 54 anos, que precisam de atendimento psicológico. Este Membro tem que lidar com diversas questoes da vida, e busca orientação nos profissionais de saude para lidar com problemas de origens diversas. 

> **Profissional de Psicologia** cadastrados na ONG, com idade entre 23 e 35 anos. Estes profissionais são universitarios e precisam, vez por outra, de orientação por parte do coordenador. Alem disso, estes profissionais dispoem de um tempo limitado que deve ser bem aproveitado nos atendimentos.

> **Coordenador dos profissionais** dispostos na ONG, com idade entre 40 e 60 anos. Os coordenadores estão dispondo de um tempo relativo nos projetos e lidam com varios casos, dentro e fora da ONG. Estes coordenadores são tambem academicos. Gostam de ler livros e noticias. 

## Histórias de Usuários

A partir  da  compreensão  do  dia  a  dia  das  personas  identificadas  para  o projeto,  foram registradas as seguintes histórias de usuários.



|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`                                                   |PARA ... `MOTIVO/VALOR`                                                                           |
|--------------------|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
|Membro da Comunidade	| me cadastrar no sistema	| receber atendimento psicologico	
|Coordeandor	|  habilitar profissionais	| realizarem atendimentos	
|Profissional de Psicologia	| manteresse particular	| visualizar depoiser compartilhadas posteriormente	
|Membro da Comunidade	| agendar horario	| Para atendimento	
|Membro da Comunidade	| selecionar o profissional	| receber atendimento segundo a disponibilidade	
|Profissional de Psicologia	| informar agenda disponivel	| realizar atendimento	
|Coordeandor	| acompanhar consultas	| observar desempenho do profissional	

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

A  tabela  a  seguir  apresenta  os  requisitos  do  projeto,  identificando  a  prioridade em  que  os mesmos devem ser entregues.


|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário se cadastre no sistema | Alta | 
|RF-002| Permitir que o psicólogo se cadastre no sistema | Alta | 
|RF-003| Permitir que o usuário crie agendamentos com os psicólogos disponíveis da plataforma  | Alta |
|RF-004| Permitir que o usuário interaja com o psicólogo | Alta |
|RF-005| Permitir que o usuário veja os psicólogos disponíveis | Média |
|RF-006| Permitir que o usuário atualize seus dados no sistema  | Média |
|RF-007| Permitir que o psicólogo atualize seus dados no sistema | Média |
|RF-008| O site deve gerar um relatório gerencial mensal.   | Baixa |

### Requisitos não Funcionais

O quadro abaixo descreve os requisitos não funcionais que o projeto atenderá.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Login integrado com redes sociais | MÉDIA | 
|RNF-002| A solução deve ser desenvolvido em Java |  BAIXA | 
|RNF-003| O usuário não deve esperar mais que 3 segundos na mudança entre uma tela e outra no aplicativo |  MÉDIA | 
|RNF-004| O sistema deve ser compacto, de fácil carregamento nos dispositivos dos usuários |  BAIXA | 
||

## Restrições

No quadro abaixo apresentamos as limitações à execução do projeto. 

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue antes do fim do semestre letivo. |
|RE-02| O projeto deverá ser executado pelos 4 integrantes da equipe desenvolvedora. |
|RE-02| O projeto deverá ser entregue com todos os seus requisitos funcionais. |


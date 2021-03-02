# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas
> O aplicativo será direcionado a equipes de psicólogos voluntários que atuam em ONGs e equipes gestoras responsáveis ​​pela coordenação dos serviços. Além disso, é necessária a  prestação de serviços aos residentes da comunidade que necessitam de atendimento psicológico

## Histórias de Usuários

A partir  da  compreensão  do  dia  a  dia  das  personas  identificadas  para  o projeto,  foram registradas as seguintes histórias de usuários.


|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`                                                   |PARA ... `MOTIVO/VALOR`                                                                           |
|--------------------|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
|Kleber jacques      | visualizar as notícias mais relevantes do momento                                    | visualizar as notícias mais relevantes do momento                                                |
|Marco Antonio       | visualizar notícias mais alinhadas com minha área de atuação                         | gastar menos tempo lendo notícias e dar foco naquelas que estão relacionadas com o meu trabalho  |
|Kleber jacques      | manter um registro de notícias específicas sobre as quais possuo interesse particular| visualizar depois e manter um histórico de notícias que possam ser compartilhadas posteriormente |
|Kleber jacques      | fazer comentários em notícias e reportar minha opinião                               | discutir com grupos de interesse comum                                                           |
|Marco Antonio       | compartilhar notícias nas redes sociais em que faço parte                            | poder discutir com os amigos e colegas de trabalhos sobre temas de interesse                     |
|Marco Antonio       | poder realizar uma pesquisa sobre notícias acerca de um tema específico              | localizar tópicos específicos e conseguir maior objetividade em algumas leituras                 |
|Kleber jacques      | ler notícias tanto no desktop quanto no celular                                      | ocupar o tempo quando estou esperando algo (ex: filas de supermercado)                           |
|Marco Antonio       | quero saber a data e a fonte das notícias lidas                                      | confiar no conteúdo passado e na atualidade das notícias que recebo                              |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

A  tabela  a  seguir  apresenta  os  requisitos  do  projeto,  identificando  a  prioridade em  que  os mesmos devem ser entregues.


|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve apresentar na página principal notícias dinâmicas obtidas por meio de canais de notícias da Internet (API) | Alta | 
|RF-002| O site deve apresentar, para cada notícia, uma imagem correspondente ao assunto apresentado (thumbnail)   | Média |
|RF-003| O site deve permitir ao usuário visualizar o texto completo da notícia com todos os detalhes da publicação  | Média |
|RF-004| O site deve oferecer um menu adicional que permita ao usuário visualizar notícias de fontes distintas (sources).  | Média |
|RF-005| O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar um texto específico que será informado na caixa de pesquisa.  | Alta |
|RF-006| O site deve apresentar permitir visualizar as informações de contatos do mantenedor do site  | Média |
|RF-007| O site deve permitir o compartilhamento de notícias visualizadas em plataformas de redes sociais   | Baixa |
|RF-008| O site deve permitir salvar notícias preferidas  | Baixa |
|RF-009| O site deve permitir verificar as notícias salvas como preferidas   | Baixa |
|RF-010| O site deve permitir que usuários possam comentar notícias   | Baixa |
|RF-011| O site deve exibir os comentários registrados juntamente com a notícia exibida  | Baixa |


### Requisitos não Funcionais

O quadro abaixo descreve os requisitos não funcionais que o projeto atenderá.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Login integrado com redes sociais | MÉDIA | 
|RNF-002| O aplicativo deve ser desenvolvido para Android e IOs |  ALTA | 
|RNF-003| O usuário não deve esperar mais que 3 segundos na mudança entre uma tela e outra no aplicativo |  MÉDIA | 
|RNF-004| O aplicativo deve ser compacto, não ocupando muita memória nos dispositivos dos usuários |  BAIXA | 
|RNF-005| O aplicativo deve ser desenvolvido em Java |  BAIXA | 


## Restrições

No quadro abaixo apresentamos as limitações à execução do projeto. 

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|RE-01| O projeto deverá ser entregue antes do fim do semestre letivo. |
|RE-02| O projeto deverá ser executado pelos 4 integrantes da equipe desenvolvedora. |
|RE-02| O projeto deverá ser entregue com todos os seus requisitos funcionais. |


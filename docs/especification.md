# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto.

Caso deseje atribuir uma imagem a sua persona, utilize o site https://thispersondoesnotexist.com/

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários


|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Administrador  | Disponibilizar formas de contato   | Agilizar o processo de adoção                   |
|Administrador  | Cadastrar ONGs mais próximas       | Facilitar a adoção                              |
|Administrador  | Criar filtros para o aplicativo    | Para que a escolha do animal ideal seja efetiva |
|Administrador  | Disponibilizar atualizações        | Promover a fluidez do aplicativo                |
|Administrador  | Cadastrar várias ONGs              | Fornecer mais opções para o cliente             |
|Administrador  | Disponibilizar adaptações para     | Para que seja accessível para todos             |
|               |  todos os tipos de dispositivos    |                                                 |
|Administrador  | Layout acessível                   | Facilitar a navegação do usuário                |

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                  |
|Usuário do sistema | Saber detalhes sobre o animal                   | Para escolher o animal ideal               |
|Usuário do sistema | Ter respostas rápidas                           | Tirar as dúvidas existentes                |
|Usuário do sistema |Facilidade na navegação                          | Facilitar a adoção                         |
|Usuário do sistema | Ter acesso a dados sobre as ONGs                | Para verificar se elas são confiáveis      |
|Usuário do sistema | Ter dicas sobre como cuidar melhor de um animal | Gerar conforto e segurança para o pet      |
|Usuário do sistema | Poder compartilhar informações                  | Para engajar novas pessoas a adotarem      |
|Usuário do sistema |Fazer doações online                             | Para ajudar as ONGs deforma rápida e fácil |



> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito                                                                               | Prioridade | 
|------|-----------------------------------------|----| 
|RF-001| Cadastro de Usuário: O sistema deve permitir que doadores e adotantes criem                             | MÉDIA |
contas com e-mail e senha.     

|RF-002|  CRUD de Animais: O usuário doador deve conseguir cadastrar, visualizar, editar e                       | ALTA  |
excluir anúncios de animais.

|RF-003| Atributos do Pet: O cadastro deve incluir campos obrigatórios: Nome, Espécie                            | ALTA  | 
(Cão/Gato/Outros), Porte (Pequeno/Médio/Grande), Sexo e Idade aproximada.

|RF-004| Galeria de Fotos: O sistema deve permitir o upload de pelo menos uma foto por                           | MÉDIA | 
animal cadastrado.    

|RF-005| Formulário de Contato: O sistema deve disponibilizar um botão de WhatsApp ou                            | MÉDIA | 
chat interno para iniciar a conversa sobre a adoção.
                   


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Responsividade: A interface deve ser adaptável para dispositivos móveis, garantindo                 | ALTA  |
acessibilidade em tablets e smartphones.
 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 

|RF-003| Atributos do Pet: O cadastro deve incluir campos obrigatórios: Nome, Espécie                            | ALTA  | 
(Cão/Gato/Outros), Porte (Pequeno/Médio/Grande), Sexo e Idade aproximada.

|RF-004| Galeria de Fotos: O sistema deve permitir o upload de pelo menos uma foto por                           | MÉDIA | 
animal cadastrado.     

|RF-005| Formulário de Contato: O sistema deve disponibilizar um botão de WhatsApp ou                            | MÉDIA | 
chat interno para iniciar a conversa sobre a adoção.
                   
Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

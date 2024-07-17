# CAPÍTILO 02 - Processos

### PROCESSO DE SOFTWARE

É necessario apresentar as variáveis do produto de software (preco, tempo ...)

### LINHA DE CÓDIGO NÃO É TIJOLO

Na engenharia tradicional o modelo é o waterfall, duas partes: planejamento e execução sequenciada

A criação do produto de software é de inteira responsabilidade do programador

Normalmente o processo de produção de software segue uma linearidade
""""O esforço de software está ligado ao tempo gasto (quantidade de horas)""""

## Manifesto Ágil

    Por meio deste trabalho, passamos a valorizar:

    Indivíduos e interações, mais do que processos e ferramentas

    Software em funcionamento, mais do que documentação abrangente

    Colaboração com o cliente, mais do que negociação de contratos

    Resposta a mudanças, mais do que seguir um plano.

- Começo 2001

A principal característica são os **ciclos (iterações) curtos e iterativos de desenvolvimento**, o sistema é criado de forma gradativa, sendo que as partes mais importante são criadas primeiro e **validação constante do cliente**

- Menor ênfase em documentação
- Menor ênfase em planos detalhados
- Inesistência de uma fase dedicada ao design
- Desenvolvimentos em times pequenos (muito usado a programação em pares)

### Métodos Ágeis

**Scrum, XP, Kanban**

#### 1.XP

`Kent Beck- 1999`

O XP segue o padrão dos métodos ágeis, é um método mais leve onde existem requisitos sujeitos a mudanças.
Adota cilcos curtos e iterativos de desenvolvimento em equipes pequenas.
O método XP defende um conjunto de práticas, valores e princípios para o desenvolvimento de softwares.  
Não existe uma etapa dedicada somente ao design, o XP promove um design incremental.  
Cada projeto deve ter um representante do cliente, uma das funções desse representante é de validar as histórias de usuários (user stories) e priorizar as mais importantes.  
A duração de uma história é estimada em stori point. Os story points seguem a sequencia de ficonacci (1,2,3,5,8,13,...)

Os tres **valores** principais: comunicação, simplicidade e feedback, esses valores buscam garantir que erros serão evitados e riscos desnecessários sejam tomados.

    Planeje-se para jogar fora partes de seu sistema, pois você fará isso.

Os **princípios** servem para ligar os valores e as práticas. Humanidade, economicidade benefícios múltiplos, melhorias contínuas, falhas acontecem, baby steps, responsabilidade pessoal e mundo real. Esses princítos visam garantir que a criação de sotfware seja feita de uma forma que garanta a maior eficiencia de tempo e custo e que as pessoas que desenvolverão o software trabalhem com responsabilidade e confiança na equipe e no processo.

As **práticas** de desenvolvimento servem para nortear o desenvolvimento do software e garantir q ele seja o mais confiável possível. Design incremental, programação em pares, propriedade coletiva do código, testes automatizados, desenvolvimeto dirigido por testes, build automatizado, integração contínua.

#### Scrum

`Jeffrey Sutherland e Ken Schwaber-1995`

O Scrum é um método ágil, incremental e iterativo para o desenvolvimento de projetos. Diferente do XP o scrum não serve apenas para projetos de desenvovimento de software, o que fez com que ele se tornasse o método ágil mais conhecido. No scrum acontecem algumas definições que são os papéis, artefatos e eventos.

Os **Papéis** no scrum são :`Dono do projeto`- tem a mesma função do Representante dos clientes no XP; `Scrum Master`- é um especialista em scrum e cabe a ele resolver alguns problemas durante o desenvolvimento, mas o scrum master não pe um gerente tradicional, no scrum todos do time tem o mesmo nível hierárquico; `Desenvolvedores`- são as pessoas que vão fazer os códigos, eles devem ter capacidades múltiplas pois o scrum defende q um projeto não deve depender de membros externos.

Os **Artefátos** no scrum são : `Backlog do produto`- é uma lista de histórias validadas e priorizadas pelo Dono do produto, mas é um artefato dinâmico, podendo sofrer alterações no decorrer do desenvolvimento; `Sprint`- é o nome dado pra uma iteração, no final de cada sprint é esperado um produto potencialmente pronto.

Os **Eventos** no scrum são: `Planejamento da sprint` - é uma reunião que feita para definir as histórias que serão implementadas na sprint, a primeira parte é o dono do projeto definir quais as histórias desejadas e o time estipular a velocidade da implementação e em seguida o time quebra as histórias em tarefas e estimam a duração delas; `Backlog da sprint` - é uma lista das tarefas e da duração da sprint, assim como o backlog do produto o backlog da sprint é um artefato dinâmico e pode sofrer alterações sem mudar o objetivo da sprint (_sprint goal_); `Reuniões diárias`- a proposta inicial é de ser um reunião rápida que se possível deve ser feita em pé e deve durar no máximo 15 minutos, cada menbro de ve responder 3 perguntas: o que ele fez, o que está fazendo e se está enfrentando algum problema mais sério na sua tarefa; `Revisão da sprint` - é uma reunião onde o time apresenta os resultados da sprint para o dono do projeto, que pode ou não sujerir mudanças; `Retrorspectiva`- é uma reunião do time de desenvolvedores com o objetivo de refletir o sobre os processos e ferramentas usadas; `Time box` - é uma tabela como a duração esperada de cada parte do projeto.

#### Kanban

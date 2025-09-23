# **Sistema de Gestão de Manutenção de Veículos:** RevisaCar

Trabalho de Experiencia do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Enrico Nascimento Silva

## Resumo

A aplicação RevisaCar é um sistema de gestão de manutenção veicular voltado para proprietários de automóveis. O objetivo é permitir o registro de manutenções realizadas, o planejamento de futuras revisões e o acompanhamento dos custos envolvidos. A plataforma oferece um painel intuitivo com histórico de serviços, alertas automáticos de revisões periódicas e relatórios de gastos, ajudando o usuário a manter seu veículo em bom estado, evitando imprevistos e reduzindo custos a longo prazo.

## Introdução

- Apresente uma contextualização para o problema que o serviço ou poduto proposto irá resolver e por quê esse tipo de aplicação é necessária.
- **Resposta**: Muitos proprietários de veículos enfrentam dificuldades em manter um controle organizado das manutenções realizadas, como trocas de óleo, revisões, alinhamentos e substituições de peças. Em geral, essas informações ficam dispersas em notas fiscais, planilhas ou simplesmente na memória do dono, o que aumenta as chances de esquecer revisões importantes, gerar gastos inesperados ou até comprometer a segurança do veículo.
- Em uma única frase, resuma o objetivo do serviço ou poduto.
- **Resposta**: simplificar o registro, o planejamento e o acompanhamento de manutenções de veículos, oferecendo alertas e relatórios de forma prática e acessível.
- Que tipo de experiência o serviço ou poduto deve proporcionar para os usuários?
- **Resposta**: O Usuário deve sentir segurança e tranquilidade ao ultilizar o sistema, percebendo que possui um "assistente pessoal de manutenção" para o seu carro. A experiência deve ser intuitiva, clara e organizada, ajudando a economizar tempo, reduzir custos e prolongar a vida útil do automóvel.

## Publico Alvo

- Determine o seu público alvo:
- **Resposta**: O RevisaCar é destinado a proprietários de veículos que desejam manter o controle das manutenções de forma simples e acessível. O sistema é voltado tanto para motoristas comuns, que precisam acompanhar revisões periódicas, quanto para motoristas profissionais que dependem do carro como fonte de renda.

### Personas

- Descreva as personas que irão interagir com a aplicação ou produto. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o serviço ou poduto deve guardar?
- **Resposta**: Dados pessoais básicos: nome, e-mail, telefone (para contato e notificações).

Perfil do usuário:

Motorista particular -> informações do veículo (modelo, ano, quilometragem, placa).

Gestor -> dados de múltiplos veículos (caso tenha mais de um) e preferências de relatórios.

Preferências de notificação: alerta por e-mail, SMS ou notificação no app.

Histórico de uso: revisões realizadas, custos registrados, datas e oficinas utilizadas.

Configurações adicionais: lembretes personalizados (ex: “alertar a cada 10 mil km” ou “gerar relatório mensal”).

  - **Persona primaira** -> João Ferreira, 32 anos – “Organização para evitar imprevistos”

João é um analista de sistemas, casado, sem filhos, que utiliza seu carro diariamente para ir ao trabalho e também em viagens ocasionais de fim de semana. Apesar de ser organizado em sua vida profissional, João costuma esquecer das datas de revisões e troca de peças do veículo. Ele já passou por situações de gastos inesperados, como a necessidade urgente de trocar a correia dentada e pneus, o que trouxe frustração e impacto financeiro.

Seu objetivo é manter um histórico confiável das manutenções, controlar gastos e evitar surpresas. João tem boas habilidades com tecnologia e está acostumado a usar aplicativos de bancos e delivery, mas não tem o hábito de usar planilhas para organização. Ele deseja um sistema simples, que registre as manutenções, alerte sobre próximas revisões e gere relatórios claros sobre custos.

No seu dia a dia, suas tarefas relacionadas ao carro são levar o veículo para revisões básicas (óleo, alinhamento, pneus), acompanhar o consumo de combustível e planejar pequenas viagens. Ele interage principalmente com a oficina mecânica e concessionárias, mas gostaria de ter mais autonomia para prever custos futuros.

Seus principais requisitos são praticidade e confiabilidade: não quer perder tempo preenchendo muitas informações, mas deseja receber alertas úteis e fáceis de interpretar. Sua expectativa é que o RevisaCar funcione como um “diário automático” de manutenção, ajudando-o a tomar decisões financeiras melhores e prolongar a vida útil do veículo.

  - **Persona secundária** -> Roberto Martins, 50 anos – “Controle esporádico para ter confiança”

Roberto é gerente de uma pequena empresa de entregas urbanas. Ele não usa o carro pessoalmente no dia a dia, pois conta com motoristas contratados, mas acompanha periodicamente o estado dos veículos da frota. Seu envolvimento direto com a manutenção é baixo, mas ele precisa garantir que os automóveis estejam em bom estado para não comprometer o negócio.

O principal objetivo de Roberto é ter relatórios claros e rápidos sobre custos de manutenção, revisões feitas e próximas datas críticas. Ele não deseja usar o sistema diariamente, mas gosta de acessar a cada duas ou três semanas para avaliar indicadores, como gastos mensais por veículo e previsões de manutenção futura.

Suas habilidades com tecnologia são medianas: utiliza sistemas de gestão financeira da empresa, planilhas de custos e aplicativos bancários, mas não gosta de perder tempo preenchendo dados. Ele valoriza praticidade e informações resumidas.

As tarefas que realiza em relação ao RevisaCar são: verificar relatórios de custos, validar se as manutenções estão sendo feitas no prazo e eventualmente cruzar essas informações com os registros financeiros da empresa. Ele mantém contato com motoristas e mecânicos apenas de forma indireta, quando há problemas ou necessidade de aprovar despesas.

Os requisitos de Roberto são simplicidade no acesso, visualização em formato de dashboard e relatórios exportáveis. Sua expectativa é que o RevisaCar funcione como um painel de controle gerencial, fornecendo informações suficientes para tomada de decisão sem que ele precise se aprofundar nos detalhes do dia a dia da manutenção.

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
- João Ferreira (*Persona Primária*)
  - O que o usuário vê: João vê seu carro na garagem todos os dias, trânsito intenso no caminho para o trabalho, propagandas de concessionárias e oficinas oferecendo serviços de manutenção. Ele observa também notificações do banco sobre gastos inesperados quando precisa arrumar o carro.
  - O que o usuário ouve: Comentários de amigos e colegas sobre experiências ruins com oficinas ou gastos altos com revisões atrasadas. Propagandas de rádio e internet sobre promoções de manutenção preventiva. Em casa, escuta a esposa preocupada com os custos do carro.
  - O que o usuário diz e faz: Costuma dizer que “manutenção de carro é um gasto sem fim”. Quando lembra, pesquisa preços e prazos no Google ou pergunta para conhecidos. Anota algumas informações em papel ou no celular, mas raramente mantém isso organizado.
  - O que o usuário pensa e sente: João sente ansiedade e frustração quando surge um problema inesperado. Pensa que poderia se organizar melhor, mas considera trabalhoso. Gostaria de ter um jeito prático de acompanhar o carro, como um “assistente digital” que lembrasse ele das revisões.
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: Esquecer datas importantes de manutenção, gastar mais do que o planejado pela falta de controle e não confiar totalmente em oficinas
  - Ganhos: Receber alertas antes de ter problemas, ter um historico centralizado para consultas rapidas e economia de dinheiro e tempo
- Roberto Martins (*Persona Secundária*) 
- O que o usuário vê: Roberto vê relatórios de custos da empresa, planilhas financeiras e gráficos de faturamento. Observa os carros da frota sendo usados diariamente pelos funcionários. Também vê mensagens de motoristas relatando problemas mecânicos ou solicitando manutenção.
  - O que o usuário ouve: Conversas com motoristas reclamando de revisões caras. Conselhos de amigos empresários para manter controle rígido de gastos com veículos. Feedback da equipe administrativa cobrando previsões de custos.
  - O que o usuário diz e faz: Costuma dizer: “preciso de números claros, não de detalhes técnicos”. Quando acessa o sistema, vai direto nos relatórios, dashboards ou resumos. Usa o RevisaCar esporadicamente, mas sempre para validar custos e confirmar se a manutenção está sendo feita.
  - O que o usuário pensa e sente: Roberto sente-se responsável pela saúde financeira da empresa. Pensa que precisa ter confiança nos relatórios sem perder tempo. Não quer ser sobrecarregado com notificações, prefere informações consolidadas. Sente tranquilidade quando vê que tudo está sob controle.
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: Perder tempo com excesso de informação técnica, não conseguir prever custos futuros e dependência de motoristas para avisar sobre problemas
  - Ganhos: Acesso a relatórios claros e exportáveis, controle macro dos custos da frota e poder tomar decisões rápidas sem depender de terceiros

## Contexto de uso

- Descreva o ambiente em que o serviço ou poduto deve ser utilizado.
  - O RevisaCar será usado principalmente em dispositivos móveis (smartphones), mas também em computadores via navegador. O ambiente de uso é cotidiano: em casa, no trabalho ou em trânsito. Para o motorista particular (persona primária), a utilização ocorre em momentos de organização pessoal, como antes de viajar ou após realizar uma manutenção. Para o gestor (persona secundária), o uso acontece em ambientes administrativos, como escritórios, com acesso a relatórios e dashboards.
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
  - O usuário primário (motorista particular) está inserido em um contexto social de classe média, buscando economia e segurança para a família. Culturalmente, está acostumado a usar aplicativos no dia a dia, mas nem sempre tem disciplina para registrar manualmente informações.
O usuário secundário (gestor) está inserido em um ambiente empresarial, preocupado com custos e previsibilidade financeira. Seu contexto cultural valoriza relatórios, números e indicadores que auxiliem na tomada de decisão.
- Quais informações sobre o ambiente, o serviço ou poduto deve guardar antes de iniciar a interação?
  - Quilometragem atual do veículo.
  - Data da última revisão realizada.
  - Tipos de serviços de manutenção mais comuns (troca de óleo, pneus, freios, etc.).
  - Custos relacionados a cada manutenção.
  - Preferências de notificação (quando e como o usuário deseja ser alertado).
  - Para gestores: agrupamento de veículos e relatórios comparativos.
- O que normalmente deve estar acontecendo com o ambiente quando o usuário interagir com o serviço ou poduto?
  - Motorista particular (primário): após sair da oficina, registrando uma manutenção, antes de viajar, conferindo se o carro está em dia, ou em casa, organizando as contas mensais.
  - Gestor (secundário): no escritório, acessando o sistema para verificar relatórios de custos, validar previsões de manutenção e confirmar se os veículos da empresa estão em condições adequadas de uso.

## Jornada do usuário

- Criar uma narrativa para o o seu serviço ou poduto com o usuário.
  - *Resposta:* O motorista João, após ter um gasto inesperado com a troca de pneus, decide organizar melhor a manutenção do seu carro. Ele acessa o RevisaCar, cadastra seu veículo e começa a registrar manutenções já feitas. Com o tempo, ele passa a receber alertas de revisões futuras, consulta relatórios no dashboard e percebe maior controle sobre seus custos, evitando surpresas.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - *Resposta:* O usuário cria uma conta -> cadastra o veículo -> registra a primeira manutenção -> consulta o dashboard -> recebe alertas de revisões -> realiza novas manutenções -> atualiza o histórico -> acompanha custos e relatórios -> exporta ou arquiva os dados quando troca de carro ou encerra o uso. 
  - Descreva o que acontece ou pode acontecer passo a passo
    - Acessa o site ou app.
    - Cria conta pessoal.
    - Cadastra dados do veículo (modelo, ano, placa, quilometragem).
    - Insere a primeira manutenção (troca de óleo, pneus, etc.).
    - Visualiza o dashboard inicial com custos e status do veículo.
    - Recebe alertas automáticos de próximas revisões.
    - Registra novas manutenções conforme ocorrem.
    - Consulta relatórios de gastos e histórico.
    - Exporta ou arquiva informações quando necessário.
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?
    - Começa: quando o usuário acessa o sistema pela primeira vez, cria uma conta e cadastra o veículo.
    - Desenvolve-se: ao longo do uso, registrando manutenções, recebendo alertas e acompanhando o dashboard.
    - Termina: quando o usuário encerra o ciclo de uso de um veículo, exportando o histórico ou arquivando os dados, ou quando troca de carro e cadastra um novo.

## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

## Coleta de dados
Entrevista – Roteiro

Objetivo: entender hábitos, dificuldades e expectativas dos usuários em relação à manutenção de veículos.

Perguntas:

1- Como você costuma acompanhar ou lembrar das manutenções do seu veículo no dia a dia?

2- Me conte sobre uma vez em que você esqueceu ou atrasou uma manutenção. O que aconteceu nessa situação?

3- Quais são as principais dificuldades ou preocupações que você enfrenta quando pensa em manter o veículo em boas condições?

4- Imagine que você tivesse um “assistente de manutenção” sempre disponível. O que você gostaria que ele fizesse por você?

5- Quando se trata de revisões, como você acredita que seria mais útil ser lembrado?

6- Se você pudesse acompanhar os custos de manutenção ao longo do tempo, de que forma isso faria sentido para você?

7- Você já deixou de fazer alguma revisão por causa de incerteza em relação ao custo? Pode me contar como foi?

8- Quando pensa em um aplicativo desse tipo, você gostaria mais de algo simples ou algo mais detalhado? Por quê?

9- Que informações sobre o seu veículo você considera importantes de guardar em um aplicativo?

10- De que forma você gostaria de ser lembrado das revisões, considerando sua rotina e o que funciona melhor para você?

Questionário - [*Link do Form*](https://docs.google.com/forms/d/e/1FAIpQLSfn8klu8jtcZLnN_qyuM_K82WQlvd3yWMvI7sS5PJsxn4kkBw/viewform?usp=sharing&ouid=113693622296915453124)

Classificação de Cartões – Conteúdo de cada card

Objetivo: organizar a interface da aplicação de acordo com a lógica do usuário. Cada cartão representa uma funcionalidade ou elemento da interface que o usuário deve agrupar.

Cartões:


Cadastro de usuário

Cadastro de veículo

Registro de manutenção

Dashboard de custos

Histórico de serviços

Alertas de revisão

Relatórios exportáveis (PDF/CSV)

Configurações de notificações

Perfil do usuário

Preferências de alerta (quilometragem, tempo, ambos)

Relatórios gerenciais (para múltiplos veículos)

Ajuda/Suporte

## HTA — Tela Dashboard (João e Roberto)

Objetivo geral: Consultar informações e tomar decisões rápidas sobre o veículo ou frota.

Persona Primária (João — motorista particular)

Consultar estado do veículo

Visualizar informações gerais
 1.1 Ver quilometragem atual
 1.2 Ver próximas revisões
 1.3 Ver alertas críticos

Acompanhar custos
 2.1 Ver total gasto nos últimos meses
 2.2 Comparar custo atual com anterior

Ver histórico rápido
 3.1 Visualizar últimas manutenções
 3.2 Acessar histórico completo

Executar ações rápidas
 4.1 Registrar nova manutenção (+)
 4.2 Exportar relatório simples
 4.3 Configurar notificações

Persona Secundária (Roberto — gestor de frota)

Avaliar estado da frota

Visualizar indicadores
 1.1 Ver gasto total do período
 1.2 Identificar veículos com revisões atrasadas
 1.3 Ver custo médio por veículo

Filtrar veículos
 2.1 Selecionar veículo específico
 2.2 Definir período de análise
 2.3 Atualizar tabela

Analisar lista de veículos
 3.1 Conferir km e próximas revisões
 3.2 Destacar veículos em atraso

Executar ações gerenciais
 4.1 Enviar alertas para motoristas
 4.2 Exportar relatório detalhado
 4.3 Abrir histórico de um veículo
 
## GOMS — Tela Registro de Manutenção (João e Roberto)

GOAL 1: Registrar manutenção do veículo ou frota.

GOAL 1.1: Registrar manutenção como motorista particular (João).

METHOD 1.1.A: Registro rápido (seleção mínima).

(SEL.RULE: Se João estiver com pressa).
OP. 1.1.A.1: Deslocar o cursor para o botão “+”.

OP. 1.1.A.2: Clicar no botão “+”.

OP. 1.1.A.3: Clicar no campo “tipo de serviço”.

OP. 1.1.A.4: Selecionar o tipo de serviço da lista (óleo, pneus, etc.).

OP. 1.1.A.5: Deslocar o cursor para o campo “quilometragem”.

OP. 1.1.A.6: Digitar a quilometragem atual.

OP. 1.1.A.7: Deslocar o cursor para o campo “custo”.

OP. 1.1.A.8: Digitar o custo aproximado.

OP. 1.1.A.9: Deslocar o cursor para o botão “Salvar”.

OP. 1.1.A.10: Clicar no botão “Salvar”.

GOAL 1.1.A.11: Visualizar confirmação.

OP. 1.1.A.11.1: Examinar a tela para a mensagem de sucesso.

METHOD 1.1.B: Registro detalhado (quando deseja guardar mais dados).
(SEL.RULE: Se quiser histórico mais completo).

OP. 1.1.B.1: Deslocar o cursor para o botão/link “Registro Detalhado”.

OP. 1.1.B.2: Clicar para abrir o formulário completo.

OP. 1.1.B.3: Preencher campo “data”, “tipo de serviço” e “oficina”.

OP. 1.1.B.4: Clicar no botão “Anexar arquivo”.

OP. 1.1.B.5: Selecionar foto ou nota fiscal no dispositivo.

OP. 1.1.B.6: Deslocar o cursor para o botão “Salvar”.

OP. 1.1.B.7: Clicar no botão “Salvar”.

GOAL 1.2: Registrar manutenção como gestor de frota (Roberto).

METHOD 1.2.A: Registro formal (detalhado para controle financeiro).
(SEL.RULE: Se for uma manutenção individual).

OP. 1.2.A.1: Deslocar o cursor para o campo “Selecionar veículo”.

OP. 1.2.A.2: Digitar ou selecionar a placa do veículo.

OP. 1.2.A.3: Preencher os campos “tipo de serviço” e “categoria”.

OP. 1.2.A.4: Digitar “data”, “km” e “custo”.

OP. 1.2.A.5: Preencher o campo “centro de custo”.

OP. 1.2.A.6: Clicar para “Anexar nota fiscal”.

OP. 1.2.A.7: Selecionar o arquivo da nota fiscal.

OP. 1.2.A.8: Clicar em “Salvar”.

METHOD 1.2.B: Registro múltiplo (importação ou lançamento em lote).

(SEL.RULE: Se for lançar várias manutenções de uma vez).

OP. 1.2.B.1: Deslocar o cursor para o menu/botão “Importação”.

OP. 1.2.B.2: Clicar para acessar a tela de importação.

OP. 1.2.B.3: Clicar no botão “Subir arquivo”.

OP. 1.2.B.4: Selecionar a planilha CSV/PDF do dispositivo.

GOAL 1.2.B.5: Conferir dados e confirmar.

OP. 1.2.B.5.1: Examinar a pré-visualização dos dados importados na tela.

OP. 1.2.B.5.2: Deslocar o cursor para o botão “Confirmar Importação”.

OP. 1.2.B.5.3: Clicar no botão “Confirmar Importação” para registrar em lote.

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
### Dashboard
![Dashboard](./img/Dashboards.jpg)
### Registro de Veículo - Persona 1 - Carros pessoais, Poucas quantidades
![RegistroDeCarrosP1](./img/RegVeiculoPersona1.jpg)
### Registro de Veículo - Persona 2 - Frotas, Grandes quantidades de carro
![RegistroDeCarrosP2](./img/RegVeiculo.jpg)
### Registro de Manutenção
![Veículo](./img/RegManutencao.jpg)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->












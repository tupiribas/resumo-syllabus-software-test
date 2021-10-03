[TOC]

# Fundamentos de Teste de software  :beetle::computer:

> É com estrema felicidade que apresento-lhe o "RESUMÃO" sobre esse lindo e maravilhoso mundo dos testes de software. Aproveite:laughing:!

## O que é Teste de software 🤔

Atualmente, com o avanço da tecnologia, podemos considerar que, tudo pode se transformar em um software, desde uma aplicação comercial até produtos de consumo e, além de existir essas possibilidades, um software pode trazer algumas dores de cabeça quando não são testados e aprovados.

Algumas pessoas tendem a achar que testes é apenas abrir algum tipo de arquivo executável, colocar alguns valores e "Pronto testado com sucesso!". Sinto-lhe informar, meu caro leitor mas, não é bem assim. Um software pode trazer diversos benefícios a humanidade mas, ignorar as possíveis falhas existentes nele, antes de expor, pode ocasionar em muitas catástrofes com, por exemplo, pessoas, empresas, cidades, estados, países e muito mais.

### Principais atividades

💠 Planejamento de teste;

💠 Análise;

💠 Modelagem e implementação dos testes;

💠 Relatórios de progresso;

💠 Resultados de testes e avaliação da qualidade de um objeto de teste.

### 		Testes dinâmicos 🏃🏽‍♂️

> É o tipo de teste para quando **o sistema já esteja sendo usado pelo usuário** e o desenvolvedor tenha que implementar alguma funcionalidade a mais no sistema. 

### 		Testes estáticos :anchor:

> É um outro tipo de teste **usado geralmente durante o processo** de criação do sistema.

### 		Atenção  aos tipos de teste:warning:

> A análise **estática e a dinâmica se complementam** **sendo as duas realizadas no sistema**. Assim, o teste também inclui a revisão de produtos de trabalho, como requisitos, histórias de usuários e código-fonte. 

### 		Outro equívoco  sobre os conceitos de teste :fearful:

Geralmente acham que teste é aprofundar-se inteiramente na verificação de requisitos, histórias dos usuários ou outras especificações. Embora o teste envolva **verificar se o sistema atende os requisitos especificados**, além de ter a validação de que o sistema atenderá as exigências dos usuários em suas diferentes esferas.

### 		Atenção ao conceito :warning:

> A forma de como serão feitas as atividades de teste irá depender do tipo de sistema que será desenvolvido!

### 	Objetivos típicos do teste🎯 🔬

- Evitar  defeitos,  avaliar  os  produtos  de  trabalho,  como  requisitos,  histórias  de  usuários, 
        modelagem e código;
- Verificar se todos os requisitos especificados foram cumpridos; 
- Verificar  se  o  objeto  de  teste  está  completo  e  validar  se  funciona  como  os  usuários  e *stakeholders*  esperam;
- Criar confiança no nível de qualidade do objeto de teste;
- Encontrar defeitos e falhas reduz o nível de risco de qualidade inadequada do software; 
- Fornecer  informações  suficientes  aos  *stakeholders*  para  que  tomem  decisões  especialmente em relação ao nível de qualidade do objeto de teste;
- Cumprir  os requisitos ou normas contratuais, legais ou regulamentares, ou verificar  a  conformidade do objeto de teste com esses requisitos ou normas.

### 	Depende do objetivo 🎯 

> Como foi dito no tópico [Atenção ao conceito⚠](Atenção ao conceito :warning:), a forma de como serão feitos todos os testes depende do que será desenvolvido. Por conta disso, deve ser analisado o contexto do componente ou sistema que está sendo testado, do nível de teste e do modelo de ciclo de vida de desenvolvimento de software. 

### 🔶 Exemplos:

- Durante o teste do componente, um objetivo pode ser encontrar tantas falhas quanto possível, de modo que os defeitos subjacentes sejam identificados e corrigidos antecipadamente;
- Outro objetivo pode ser aumentar a cobertura de código dos testes de componentes;
- Durante o teste de aceite, um objetivo pode ser confirmar que o sistema funciona como esperado e satisfaz os  requisitos. Outro  objetivo  deste  teste pode ser fornecer informações aos *stakeholders* sobre o risco de liberar o  sistema em um determinado momento.

### Teste e depuração de código 👩🏽‍💻👨🏽‍💻:beetle:

> Teste de depuração de código são diferentes!

> A execução dos testes pode mostrar falhas causadas por defeitos no software. A depuração de código é a atividade de desenvolvimento que localiza, analisa e corrige esses defeitos.

> Os testes de confirmação imediata verificam se as correções resolveram os  defeitos.

#### 	Os desenvolvedores  💻

> Os  desenvolvedores  fazem  a  depuração  e  o  teste  de  componente associado. 

#### 	Os testadores :beetle:

> Os  testadores  são  responsáveis  pelo  teste  inicial  e  pelo  teste  de confirmação  final. No  desenvolvimento  ágil  e  em  alguns  outros  ciclos  de  vida,  os  testadores podem estar envolvidos na depuração e no teste de componentes.

## Por que o teste é necessário? 🔰

- Testes rigorosos de componentes e sistemas e sua documentação associada podem ajudar a reduzir o risco de falhas durante a operação. 

- Quando defeitos são detectados e posteriormente corrigidos, há  contribuição para a qualidade  dos  componentes  ou  sistemas.  

- O  teste  de  software também é necessário para atender aos requisitos contratuais ou legais ou aos padrões específicos do setor. 

### Envolvimento dos testadores 💡📈

#### 	Revisões de análise 🔍

> Os testadores vão rever os requisitos ou refinar as histórias dos usuários e detectando defeitos nesses produtos de trabalho.

> A identificação e remoção de defeito de requisitos reduz o risco de desenvolvimento de funcionalidade incorreta ou não testável

#### 	Participação do inicio ao fim 🏁

> Os testadores devem fazer parte de todo o processo de desenvolvimento, além de estarem em conjunto com os projetistas do sistema enquanto o sistema está sendo projetado.

> Pode aumentar o entendimento de cada parte sobre o código e como o testar. Esse aumento de compreensão pode reduzir o risco de defeitos no código e nos testes.

#### 	Verificação e validação 🔬✅

> Os testadores devem verificar e validar antes de liberar o software.

> Isso aumenta a probabilidade de que o software atenda às necessidades dos *stakeholders* e satisfaça os requisitos.

> Essas recomendações e os objetivos do teste definidos [Objetivos típicos do teste🎯 🔬](###Objetivos típicos do teste🎯 🔬), contribui para o sucesso geral do desenvolvimento e manutenção de software.

### QA e teste😃:beetle:

> As definições não são as mesmas, mas estão relacionadas.

#### 	Gestão da qualidade😃

> A gestão da qualidade inclui todas as atividades que direcionam e controlam uma organização em relação à qualidade. Elas garantem e controlam a qualidade. A garantia da qualidade contribui para a prevenção de defeitos.
> 
>O uso de análise de causa raiz para detectar e remover as causas de defeitos, juntamente com a aplicação adequada das conclusões de reuniões retrospectivas para melhorar os processos, é importante para garantir a qualidade efetiva.

#### 	Controle de qualidade em testes 🐞

> As atividades  de teste são parte do processo geral de desenvolvimento ou manutenção de software. 
>
> Como a garantia de qualidade está relacionada com a execução adequada de todo o processo, a garantia de qualidade apoia o teste.

> Diante do que foi descrito em [Objetivos típicos do teste🎯 🔬](###Objetivos típicos do teste🎯 🔬) e [Teste e depuração de código 👩🏽‍💻👨🏽‍💻:beetle:](###Teste e depuração de código 👩🏽‍💻👨🏽‍💻:beetle:) os testes contribuem para a obtenção da qualidade de várias formas.

## Erros, defeitos e falhas  ❗🧾💣

### 	Erro ❗

> Um erro acontece por conta do usuário e que pode ocasionar em um **defeito** (falha ou bug) no código do software ou em algum outro produto de trabalho relacionado.

#### 	Circunstancia dos erros ❗ 🤔

- Pressão do tempo; 
- Falha humana; 
- Participantes do projeto inexperientes ou insuficientemente qualificados; 
- Falta de comunicação entre os participantes do projeto, incluindo falta de comunicação sobre os requisitos e a modelagem; 
- Complexidade do código, modelagem, arquitetura, o problema a ser resolvido ou as tecnologias utilizadas; 
- Mal-entendidos  sobre  interfaces  intra-sistema  e  entre  sistemas,  especialmente quando  tais interações são em grande número; 
- Tecnologias novas, ou desconhecidas. 

### Defeito 🧾

> Um **defeito** (fault) é a manifestação de um **erro** e pode acarretar uma **falha**.

### 🔶 Exemplo:

> Um erro de licitação de requisitos pode levar a um defeito de requisitos, o que resulta em um erro de programação que leva a um defeito no código.

### 	Falha ou bug  💣:beetle:

> Uma **falha** (failure) é quando um **software** não cumpre seu objetivo, com **ou** sem exceção.

#### Circunstancia dos falhas 💣🤔

-  Defeitos  no  código causadas por condições  ambientais.

### 🔶 Exemplo:

> Por  exemplo,  radiação,  campos  eletromagnéticos  e  poluição  podem  causar defeitos no firmware ou influenciar a execução do software alterando as condições do hardware.

​		A execução de um código defeituoso, pode causar uma falha, mas não necessariamente em todas as 
​		circunstâncias. 

### Atenção aos falsos positivos:warning:

Nem todos os resultados inesperados de testes são considerados falhas.

> Falsos negativos são testes que não detectam defeitos que deveriam ser detectados

Falsos  positivos  podem ocorrer devido a erros na forma como os testes foram executados ou devido a defeitos nos dados de teste, no ambiente de teste ou em outro testware ou por outros motivos. 

### Atenção aos falsos negativos:warning:

> Falsos positivos são relatados como defeitos, mas na verdade não são defeitos. 

A situação inversa de falsos positivos também pode ocorrer, onde erros ou defeitos similares levam a falsos negativos.

### Defeitos, causas-raiz e efeitos 🧾🌲📉

Podem ser associados entre si.	

#### 	Causas-raiz 🌱

> As causas-raiz dos defeitos são as primeiras ações ou condições que contribuíram para a criação dos defeitos. 

#### 	Defeitos 🧾

> Os  defeitos  podem  ser  analisados  para  identificar  suas  causas-raiz,  de  modo a  reduzir a ocorrência de defeitos similares no futuro.

#### 	Efeitos 📉

> Para toda ação existe os efeitos colaterais. Os efeitos causados pela boa manutenção, ou a falta dela, pode ocasionar em muitos ou poucos defeitos.

## Os sete princípios de testes 🎰💡

### 	O teste mostra a presença de defeitos e não a sua ausência 🔍👩🏽‍💻

> Seu trabalho é **reduzir o números de defeitos no software**, mas **não garante** que não possa **ter outros defeitos existentes**.

### 	Teste exaustivo é impossível 🤯🥵

> **Verifique os riscos e prioridades**, não perca tempo com testes muito aprofundados e demorados.
>
> Testar tudo é **impossível**!
>
> Teste as **principais funcionalidades** e se estão atendendo ao que o cliente pediu.

### O teste inicial economiza tempo e dinheiro ⏰💰

> Para encontrar antecipadamente os defeitos, as atividades de teste estático e dinâmico devem iniciar o mais cedo possível no ciclo de vida de desenvolvimento de software.

> O teste no início do ciclo de vida de desenvolvimento de software ajuda a reduzir ou eliminar alterações dispendiosas.

### 	Argumentos de defeitos 📚

> Relaxe! 😎
>
> Uma pequena quantidade de defeitos podem levar a outros defeitos.
>
> "É como se fosse o efeito dominó, derrubou um, derrubou todos."

### 	Paradoxo do Pesticida ☣🐞

> Não use o mesmo "Baygon" pra o mesmo inseto, as vezes é bom mudar de tática.
>
> Quando se está testando, é sempre uma boa prática usar outras técnicas de achar o mesmo defeito.

### 	Teste depende do contexto 📃

> Como foi dito anteriormente todos os testes são diferentes diante do contexto.
>
> Você não pode usar a mesma estratégia de teste de site e-commerce em um sistema de segurança, né?

### 	A ilusão da ausência de erros 🙈🙉🙊

> O que adianta testar e concertar os defeitos se o sistema não atende as expectativas dos clientes?
>
> Mesmo que você resolva tudo, ainda pode existir a chance do sistema ficar difícil de usar.

## Processos de teste 🧭

### 	Fatores🔸

- Quais atividades de teste estão envolvidas;
- Como  essas  atividades  são  implementadas;
- Quando  essas atividades ocorrem.

### 	Processo de teste no contexto  🧭📃

- Modelo de ciclo de vida de desenvolvimento de software e metodologias de projeto utililzados; 
- Níveis de teste e tipos de teste considerados; 
- Riscos de produto e projeto; 
- Domínio do negócio; 
- Algumas restrições operacionais: 
- Orçamentos e recursos; 
- Escalas de tempo; 
- Complexidade; 
- Requisitos contratuais e regulamentares. 
- Políticas e práticas organizacionais; 
- Normas internas e externas necessárias. 

#### Aspectos gerais dos processos de teste organizacionais 💼

- Atividades e tarefas de teste; 
- Produtos de trabalho de teste; 
- Rastreabilidade entre a base de teste e os produtos de trabalho de teste.

### Critérios de cobertura 🏡

> Os critérios de cobertura podem atuar efetivamente como  indicadores-chave  de performance  (KPIs)  para  conduzir  as  atividades  que  demonstram  a realização dos objetivos de teste de software leia o [Objetivos típicos do teste🎯 🔬](###Objetivos típicos do teste🎯 🔬).

#### Execução com o uso dessa cobertura 📲

> Uma vez executados, os resultados desses testes informam aos interessados se os requisitos especificados são atendidos e se as falhas foram observadas nos dispositivos suportados.

## Atividades e tarefas de teste 📑✅🐞

### Principais atividades  🔛

- Planejamento do teste;
- Monitoramento e controle do teste;
- Análise do teste;
- Modelagem do teste;
- Implementação do teste;
- Execução do teste; 
- Conclusão do teste. 

Cada atividade pode consistir de várias tarefas e podem variar de um projeto ou lançamento para outro.

#### 			Planejamento do teste 📑

> É sempre bom planejar.
>
> O planejamento do teste definem os propósitos e a abordagem do teste para atender os objetivos dele de acordo com as restrições e seu contesto.

##### 		Produtos de trabalho do planejamento do teste📈

> Planejamento do teste geralmente incluem um ou mais planos de teste. 

> O plano de teste inclui informações de rastreabilidade com os quais outros produtos de                                                      teste serão relacionados através das informações de rastreabilidade, ler também [Rastreabilidade entre a base de teste e os produtos de trabalho de teste 📡🐞](###Rastreabilidade entre a base de teste e os produtos de trabalho de teste 📡🐞).

#### 		Monitoramento e controle de teste📊

> O **monitoramento de teste** é comparar constantemente a situação atual com o plano de teste e pode ser usado qualquer métrica de monitoramento definida no plano de teste.
>
> O tempo todo estamos tomando ações e no **controle de teste** não é diferente, ele engloba a tomada de ações para atender os objetivos do plano de teste.

##### 		Produtos de trabalho de monitoramento e controle do teste📈🔍

> Monitoramento e controle do teste geralmente incluem vários tipos de **relatórios**, incluindo relatórios de progresso do teste (produzidos em uma base contínua ou regular) e relatórios de resumo do teste (produzidos em vários marcos de conclusão).

> Todos os **relatórios de teste** devem fornecer detalhes relevantes do público sobre o progresso dele a partir da data do relatório, incluindo o resumo dos resultados da execução do teste assim que eles estiverem disponíveis.

> As preocupações de de gerenciamento de projeto também devem ser relevantes para o monitoramento do teste**, assim como a conclusão das tarefas, a alocação e uso de recursos e o esforço.

##### 		Critérios de saída para a execução do teste🏃🏽‍♂️▶

- Verificar os resultados do teste e os registros em relação aos critérios especificados de cobertura;
- Avaliar o nível de qualidade do componente ou sistema com base nos resultados e registros dos testes; 
- Determinar se são necessários mais testes.

> O progresso de teste em relação ao plano é comunicado aos *stakeholders* nos relatórios de progresso do testes, incluindo os desvios do plano e as informações para apoiar qualquer decisão de interromper o teste. 

#### 		Análise do teste 🔍🐞

> A  identificação  dos  defeitos  durante  a  **análise  do  teste**  é  um  benefício  importante, especialmente quando nenhum outro processo de revisão está sendo usado e/ou  o processo de teste está  intimamente  ligado  ao  processo  de  revisão.  

> A análise do teste determina "o que testar" em termos dos critérios de cobertura mensuráveis.

##### 			Produtos de trabalho da análise do teste📈🔬🐞

> Análise do teste incluem condições de teste definidas e priorizadas, preferencialmente onde cada uma das quais é bidirecionalmente rastreável para o(s) elemento(s) específico(s) da base de teste que a cobre.

> Para testes exploratórios, a análise do teste pode envolver a criação de [Cartas de teste](######Cartas de teste). A análise do teste também pode resultar na descoberta e no relato de defeitos na base de teste.

##### 			Principais atividades🔛

- Analisar a base de teste apropriada ao nível de teste que está sendo utilizado, como por exemplo:

  As  especificações  de  requisito:

  - Requisitos  de  negócios;
  - Requisitos  funcionais;
  - Requisitos  do  sistema;
  - Histórias  de  usuários;
  - Épicos;
  - Casos  de  uso  ou  produtos  de trabalho  semelhantes  que  especificam  o  componente funcional  ou  não  funcional desejado ou o comportamento do sistema;

  A modelagem e a implementação de informações:

  - Diagramas ou documentos de arquitetura de sistema ou software;
  - Especificações de modelagem;
  - Fluxos de chamadas;
  - Diagramas de modelagem, como por exemplo, diagramas de UML ou de entidade;
  - Especificações de interface;
  - Produtos  de  trabalho  semelhantes  que  especifiquem  componentes  ou estrutura do sistema;

  A implementação do componente ou sistema em si, incluindo:

  - Código;
  - Metadados e consultas ao banco de dados;
  - Interfaces;

  Os  relatórios  de  análise  de  risco,  que  podem  considerar os aspectos:

  - Funcionais;
  - Não-funcionais;
  - Estruturais do componente ou sistema.

- Avaliar a base de teste e os itens de teste para identificar os vários tipos de defeitos, como: 
  - Ambiguidades;
  - Omissões;
  - Inconsistências;
  - Imprecisões; 
  - Contradições; 
  - Declarações supérfluas.

- Identificar os recursos e os conjuntos de recursos a serem testados;
- Definir e priorizar as condições e teste para cada recurso com base na análise da base de teste e considerando as características funcionais, não-funcionais e estruturais, além de analisar outros fatores comerciais e técnicos e, por fim, os níveis de riscos.
- Capturar a rastreabilidade bidirecional entre cada elemento da base de teste e as condições de teste associadas.
  

Veja [Rastreabilidade entre a base de teste e os produtos de trabalho de teste 📡🐞](###Rastreabilidade entre a base de teste e os produtos de trabalho de teste 📡🐞).

> Para reduzir as chances de omitir as condições importantes de teste e definir as condições de teste mais corretas e precisas a aplicação de técnicas de teste caixa-preta, caixa-branca e experiência pode ser útil no processo de análise do teste (**essa informação será aprofundada posteriormente**).

###### 		Cartas de teste 🃏

> As cartas de teste são  típicos produtos de trabalho em alguns tipos de testes baseados na experiência. 
>
> Quando esses objetivos do teste são rastreáveis até  a  base  de  teste,  a  cobertura obtida  durante  esses  testes,  baseados  na  experiência,  podem  ser medidas.

> Essas  atividades  de  **análise  do  teste**  não  apenas verificam  se  os  requisitos  são  consistentes, expressos  adequadamente  e  completos,  mas  também validam  se  os  requisitos  capturam  adequadamente  as  necessidades  do  cliente,  do  usuário  e stakeholders.

#### Modelagem do teste 📐💡

> A análise do teste responde à pergunta “o que testar?”, enquanto a modelagem de teste responde à pergunta “como testar?”

##### Produtos de trabalho da modelagem do teste  📐💡📈

> A modelagem do teste resulta em casos de teste e conjuntos de casos de teste para exercer as condições de teste definidas na análise do teste.

> A modelagem do teste também resulta no projeto ou na identificação dos dados necessários de teste, na modelagem do ambiente de teste, e na identificação de infraestrutura e ferramentas.

> As condições de teste definidas na análise do teste podem ser mais refinadas na modelagem do teste.

##### 	Principais atividades 🔛

- Projetar e priorizar casos de teste e conjuntos de casos de teste;
- Identificar os dados de teste necessários para comportar as condições de teste e os casos de teste;
- Projetar o ambiente de teste e identificar qualquer infraestrutura e ferramenta necessária;
- Capturar a rastreabilidade bidirecional entre a base de teste, as condições de teste, os casos de teste e os procedimentos de teste, ler também [Rastreabilidade entre a base de teste e os produtos de trabalho de teste 📡🐞][###Rastreabilidade entre a base de teste e os produtos de trabalho de teste 📡🐞].

> Assim como na análise do teste, a modelagem do teste também pode resultar na identificação de tipos semelhantes de defeitos na base de teste.

#### Implementação do teste🚀🐞

> A modelagem de teste responde à pergunta "como testar?", enquanto a implementação do teste responde à pergunta "agora temos tudo para executar os testes?"

##### 	Os produtos de trabalho de implementação do teste 🚀🐞📈

- Os procedimentos de teste e seu sequenciamento;
- As suítes de teste;
- Um cronograma de execução do teste.

> Uma vez concluída a implementação do teste, a obtenção dos critérios de cobertura estabelecidos no plano de teste pode ser demonstrada por meio da rastreabilidade bidirecional entre os procedimentos e os elementos específicos da base de teste, através dos casos de teste e das condições de teste.

> A implementação do teste também pode resultar na criação e verificação dos dados de teste e do ambiente de teste.

> As condições de teste definidas na análise do teste podem ser refinadas na implementação do teste.

##### 	Principais atividades  🔛

- Desenvolver e priorizar os procedimentos de teste e, potencialmente, criar os scripts de teste automatizados;
- Criar as suítes de teste a partir dos procedimentos de teste e (se houver) os scripts de teste automatizados;
- Organizar os conjuntos de testes dentro de um cronograma de maneira que resulte em maior eficiência a execução dos testes;
- Construir o ambiente de teste (incluindo, potencialmente, equipamentos de teste, virtualização de serviços, simuladores e outros itens de infraestrutura), e verificando se tudo o que é necessário foi configurado corretamente;
- Preparar os dados de teste e garantir que eles sejam carregados corretamente no ambiente de teste;
- Verificar e atualizar a rastreabilidade bidirecional entre a base de teste, as condições de teste, os casos de teste, procedimentos de teste e suítes de teste.

#### Execução do teste 💻📱

> Durante a execução do teste, os conjuntos de testes são executados de acordo com a programação de execução do teste.

##### 	Os produtos de trabalho da execução do teste💻📱📈

- A documentação do status dos casos de teste individuais ou procedimentos de teste (p. ex., pronto para executar, passar, falhar, bloquear, ignorar deliberadamente etc.);
- Os relatórios de defeitos;
- A documentação sobre quais os itens de teste, o(s) objeto(s) de teste, as ferramentas de teste e o testware estavam envolvidos no teste.

> Uma vez concluída a execução do teste, o status de cada elemento da base de teste pode ser determinado e relatado via rastreabilidade bidirecional com o(s) procedimento(s) de teste associado(s).

##### 	Principais atividades 🔛

- Gravar os identificadores e versões do(s) item(ns) de teste ou do objeto de teste, da(s) ferramenta(s) de teste e testware;
- Executar os testes manualmente ou usando ferramentas de execução do teste;
- Comparar os resultados reais com os resultados esperados;
- Analisar as anomalias para estabelecer suas prováveis causas (p. ex., falhas podem ocorrer devido a defeitos no código, mas falsos positivos também podem ocorrer), ver também [Erros, defeitos e falhas  ❗🧾💣](###Erros, defeitos e falhas  ❗🧾💣);
- Comunicar os defeitos com base nas falhas observadas;
- Registrar o resultado da execução do teste;
- Repetir as atividades de teste como resultado de uma ação tomada por uma anomalia, ou como parte do planejado para o teste (p. ex., execução de um teste corrigido, teste de confirmação ou teste de regressão);
- Verificar e atualizar a rastreabilidade bidirecional entre a base de teste, as condições de teste, os casos de teste, os procedimentos de teste e os resultados de teste.

#### Conclusão do teste 🏁🐞

> As atividades de conclusão do teste coletam os dados das atividades de teste já concluídas para consolidar a experiência, o testware e qualquer outra informação relevante.
>
> As atividades de conclusão do teste ocorrem nos marcos do projeto, como quando um sistema de software é lançado.

##### 	Produtos de trabalho de conclusão do teste 🐞🏁📈

> Os produtos de trabalho de conclusão do teste incluem os relatórios de resumo de teste, os itens de ação para melhoria de projetos subsequentes ou iterações (p. ex., após um projeto de retrospectiva ágil), as solicitações de mudança ou os itens finalizados de backlog de produto e testware.

##### 	Principais atividades   🔛

- Verificar se todos os relatórios de defeitos estão fechados, inserindo as solicitações de mudança ou itens de lista não processada do produto para quaisquer defeitos que não foram resolvidos no final da execução do teste;
- Criar um relatório de resumo de teste para ser comunicado aos stakeholders;
- Finalizar e arquivar o ambiente de teste, os dados de teste, a infraestrutura de teste e outros testwares para posterior reutilização;
- Entregar o testware para as equipes de manutenção, outras equipes de projeto ou stakeholders que poderiam se beneficiar de seu uso;
- Analisar as lições aprendidas das atividades de teste concluídas para determinar as alterações necessárias para futuras iterações, releases e projetos;
- Usar as informações coletadas para melhorar a maturidade do processo de teste.

### Rastreabilidade entre a base de teste e os produtos de trabalho de teste 📡🐞

> Conforme mencionado no capítulo , os produtos de trabalho de teste e os nomes desses produtos de trabalho variam significativamente.

> É importante estabelecer e manter a rastreabilidade durante todo o processo de teste entre cada elemento da base de teste e os vários produtos de teste associados a esse elemento.

##### 	O que a rastreabilidade pode suportar 🤔📡

- Analisar o impacto das mudanças;
- Tornar o teste confirmado;
- Atender aos critérios de governança de TI;
- Melhorar a compreensibilidade dos relatórios de progresso do teste e dos relatórios de resumo do teste para incluir o status dos elementos da base de teste (p. ex., requisitos que passaram em seus testes, requisitos que falharam em seus testes e requisitos que têm testes pendentes);
- Relacionar os aspectos técnicos do teste com os stakeholders em termos que eles possam entender;
- Fornecer informações para avaliar a qualidade do produto, a capacidade do processo e o progresso do projeto em relação às metas de negócios.

> Algumas organizações criam seus próprios sistemas de gerenciamento para organizar os                               produtos de trabalho e fornecer a rastreabilidade de informações de que necessitam.

## A psicologia do teste 🧠🐞

> Como foi dito em [O que é teste de software🤔](O que é teste de software🤔) a falta de atenção para as possíveis falhas de software pode ocasionar em possíveis catástrofes, causando ferimentos ou até mortes de pessoas e, por conta disso, a **psicologia humana** tem efeitos importantes no teste de software.

### Psicologia humana e os testes🧠👩👨🐞

> Geralmente as pessoas tendem a achar que o teste de software seja uma atividade destrutiva, embora contribua para o progresso do projeto e a qualidade do produto (ver [QA e testes😃:beetle:](###QA e testes😃:beetle:)). 
>
> Para tentar reduzir essas percepções, as informações sobre os defeitos e as falhas devem ser comunicadas de maneira construtiva.
>
> Isso se aplica durante os **testes estáticos e dinâmicos.**

### Dicas para uma boa comunicação 😃💬

1. Comece com colaboração em vez de batalhas. Lembre a todos do objetivo comum de sistemas de melhor qualidade;
2. Enfatize os benefícios do teste:
   1. Para os autores, informações sobre defeitos podem ajudá-los a melhorar seus produtos de trabalho e suas habilidades.
   2. Para a organização, os defeitos encontrados e corrigidos durante os testes economizarão tempo e dinheiro e reduzirão o risco geral à qualidade do produto;
3. Comunique os resultados dos testes e outras descobertas de uma maneira neutra, focada no fato, sem criticar a pessoa que criou o item com defeito;
4. Escreva relatórios de defeitos objetivos e factuais e revise os resultados;
5. Tente entender como a outra pessoa se sente e as razões pelas quais ela pode reagir negativamente à informação;
6. Confirme se a outra pessoa entendeu o que foi dito e vice-versa.

### A mentalidade do testador e do desenvolvedor 👩‍💻🔍🧠👨‍💻

> Desenvolvedores e testadores tem objetivos e mentalidades diferentes e reunir essas mentalidades s ajuda a alcançar um nível mais alto de qualidade do produto.
>
> A mentalidade de um testador deve incluir curiosidade, pessimismo profissional, olho crítico, atenção aos detalhes e motivação para comunicações e relacionamentos bons e positivos.
>
> A mentalidade de um desenvolvedor pode incluir alguns dos elementos da mentalidade de um testador, porém o viés de confirmação torna difícil encontrar erros em seu próprio trabalho.

> Ter algumas das atividades de teste feitas por testadores independentes aumenta a eficácia da detecção de defeitos, o que é particularmente importante para sistemas grandes, complexos ou de segurança crítica.
>
> Testadores independentes trazem uma perspectiva que é diferente daquela dos autores de produtos de trabalho (isto é, analistas de negócios, proprietários de produtos, designers e programadores), uma vez que eles têm diferentes vieses cognitivos dos autores.

# Teste durante o ciclo de vida de desenvolvimento de software 🐞🕓👨‍💻

> Olá seja bem-vindo(a) ao segundo capítulo da nossa jornada por esse maravilhoso mundo que é o teste de software, espero que goste 😉😁!

## O que você irá aprender? 🤔

1. Modelos de ciclo de vida de desenvolvimento de software;
2.  Níveis de teste;
3. Tipos de teste;
4. Teste de manutenção.

## Modelos de ciclo de vida de desenvolvimento de software 🕓👨‍💻

> Ele descreve os tipos de atividades realizadas em cada estágio de um projeto de desenvolvimento de software e como as atividades se relacionam umas com as outras de forma lógica e cronológica.

### 	Os tipos de modelos de ciclo de vida 📝

- Cascata
- Modelo em V
- Incremental
- Evolutivo
- RAD
- Prototipagem
- Espiral
- Modelo de Ciclo de Vida Associado ao RUP

## Desenvolvimento de software e teste de software 👨‍💻🐞

> É importante o testador está familiarizado com o ciclo de vida de um desenvolvimento de software para que as atividades de teste ocorram tranquilamente.

### 	Características para um bom teste 😁👌

- Para cada atividade de desenvolvimento, existe uma atividade de teste correspondente;
- Cada nível de teste tem objetivos de teste específicos;
- A análise e a modelagem de teste para um determinado nível de teste começam durante a atividade de desenvolvimento correspondente;
- Os testadores participam de discussões para definir e refinar os requisitos e a modelagem, e estão envolvidos na revisão dos [produtos de trabalho](Produtos de trabalho do planejamento do teste📈).









# Referências 

------

[Syllabus Foundation Level](https://bstqb.org.br/b9/doc/syllabus_ctfl_2018br.pdf).pdf


# Breve resumo de diagramas

Uma breve compilação de material (curadoria de conteúdo digital) sobre diversos diagramas utilizados na disciplina de Engenharia de Software, projeto de software, arquitetura de sistemas e bancos de dados. "Resumo dos diagramas mais comuns" que usamos nestas disciplinas. Este não é um guia definitivo, mas um pequeno tutorial compilado para auxiliar alunos e devs. 





```
Observação:
Este material é o mínimo necessário nas áreas de: 
a) engenharia de software;
b) documentação de software;
c) arquitetura de software e sistemas;
d) modelagem visual de software.
Este material esta em construção. 
```



---
# Sumário

- [Breve resumo de diagramas](#breve-resumo-de-diagramas)
- [Sumário](#sumário)
- [1. Definições](#1-definições)
- [2. DER](#2-der)
  - [2.1. Entidade](#21-entidade)
  - [2.2. Atributos](#22-atributos)
  - [2.3. Relacionamentos](#23-relacionamentos)
- [3. DFD](#3-dfd)
- [4. UML](#4-uml)
  - [4.1. Diagrama de classes](#41-diagrama-de-classes)
  - [4.2. Diagrama de casos de uso](#42-diagrama-de-casos-de-uso)
  - [4.3. Diagrama de atividades](#43-diagrama-de-atividades)
  - [4.4. Diagrama de sequência](#44-diagrama-de-sequência)
  - [4.5. Diagrama de componentes](#45-diagrama-de-componentes)
    - [4.5.1. Interfaces](#451-interfaces)
    - [4.5.2. Artefatos](#452-artefatos)
  - [4.6. Diagrama de pacotes](#46-diagrama-de-pacotes)
  - [4.7. Diagrama de implantação](#47-diagrama-de-implantação)
- [5. Fundamental Modeling Concepts (FMC)](#5-fundamental-modeling-concepts-fmc)
- [6. Criando diagramas em páginas do github:](#6-criando-diagramas-em-páginas-do-github)
- [7. BPMN](#7-bpmn)
- [8. Referências](#8-referências)
- [9. Como citar esta página em seus trabalhos, artigos ou outras referências:](#9-como-citar-esta-página-em-seus-trabalhos-artigos-ou-outras-referências)
  - [9.1. Citação bibliográfica:](#91-citação-bibliográfica)
  - [9.2. Citação bibtex para Latex:](#92-citação-bibtex-para-latex)
- [10. Lista de ferramentas](#10-lista-de-ferramentas)
- [11. Comentários finais](#11-comentários-finais)
- [12. Avisos, licença, estatísticas...](#12-avisos-licença-estatísticas)
  - [12.1. Avisos](#121-avisos)
  - [12.2. Licença](#122-licença)
  - [12.3. Estatísticas do repositórios do Prof. Monteiro](#123-estatísticas-do-repositórios-do-prof-monteiro)




<!---

     comentario 0
     ![Nova lei de licitação](https://raw.githubusercontent.com/monteiro74/lab_inova_serv_pub/main/imagens/nova_lei_licitacao.jpeg)

```
exemplo de caixa de texto
```
-->





---
# 1. Definições

Um diagrama é um desenho mostrando uma estrutura ou representação esquemática de algo (como uma máquina ou sistema), de forma a apresentar simplificadamente sua estrutura e/ou funcionamento. <br>

Definição 1: *Diagrama é uma representação gráfica usada para demonstrar um esquema simplificado ou um resumo sobre um assunto*.<br>
Fonte: https://www.significados.com.br/diagrama/

Definição 2: *O diagrama é um gráfico que apresenta informação de forma esquematizada e relacionada a algum tipo de área, seja na política ou economia de algum país ou empresa, e que aparece representada numericamente e em forma de tabela*.<br>
Fonte: https://conceitos.com/diagrama/

Definição 3: *Delineação; modo de representação feito através de gráficos, de esquemas, de linhas, de pontos: diagrama elétrico. Esboço; demonstração dos aspectos gerais de alguma coisa: diagrama do televisor. Tipo de maquete que contém o cenário usado nas filmagens*. <br>
Fonte: https://www.dicio.com.br/diagrama/


O diagramas aqui apresentados permitem que os sistemas possam ser estruturados de forma modular. A modularidade pode ser entendidade como:

* É a separação dos elementos constitutivos de um corpo.
* É a desagregação de seus componentes e estruturas menores.
* É a transformação do sistema em pequenas partes de forma que possam ser tratadas separadamente, porém continuam tendo suas funcionalidades mantidas para que o conjunto possa operar.
* Permite que o sistema ou software possa ser divido em partes distintas.

![Exemplo de modularidade](https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/modularidade.png)


Onde se aplica a modelagem visual:

![Modelagem visual](https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/modelagem_visual.png)


[Voltar ao sumário](#sumário)<br>





---
# 2. DER

O Diagrama de Entidade Relacionamento (DER), é um tipo de diagrama que apresenta as entidades de um sistema; estas entidades são conectadas por relacionamentos, as entidades possuem internamente atributos. Este diagrama é utilizado para modelar bancos de dados, também pode representar regras de negócio utilizadas pelas empresas. Também permite perceber as conexões lógicas entre "as coisas" com as quais se deseja representar informações. O criado deste diagrama é o Professor Peter Chen ([Peter Pin-Shan Chen](https://en.wikipedia.org/wiki/Peter_Chen)) na década de 1970 naSloan School of Management no MIT publicado em “*The Entity-Relationship Model: Toward a Unified View of Data*". O trabalho de DER contribuiu para o modelo de Classes e posteriormente com a UML. <br>

São componentes de um DER: entidades, atributos e relacionamentos. Os diagramas entidade relacionamento também proporcionam um meio de comunicação. Os diagramas entidades relacionamento são também chamados de diagram ER, Modelo ER. São diagramas estruturais utilizados principalmente para o projeto de um banco de dados (relacional e/ou objeto relacional). <br>


Na figura abaixo temos 3 exemplos, esta figura esta dividida ao meio, prefira as notações da direita.<br>


<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/der.png" alt= “DER” width="600" height="420">

[Voltar ao sumário](#sumário)<br>


## 2.1. Entidade


As entidades são "**as coisas**" que queremos representar e guardar informações sobre. São exemplos de entidades carros, objetos, lugares, pessoas, veículos, etc. As entidades são representadas por um retângulo com seu nome no centro. Na figura abaixo temos várias formas de notação diferentes para representar uma entidade.<br>


![Exemplo de entidades](https://github.com/monteiro74/diagramas_resumo/blob/main/imagens/entidades.jpg?raw=true "Exemplo de entidades")

[Voltar ao sumário](#sumário)<br>








## 2.2. Atributos

Os atributos dão características às entidades. São os elementos básicos que ajudam a formar e dar identidade às entidades. São os tijolos básicos das entidades e sua compreensão. Atributos também podem ser características de relações. <br>


```
Observação:
Algumas ferramentas de diagramação os atributos estão conectados nas
entidades e representados em forma oval. É bom citar que esta é uma das
piores formas de representação de atributos em entidades, pois os diagramas
tendem a crescer conforme o analista vai melhorando ou especificando mais
detalhes nos diagramas, essa abordagem de usar  balões como atributos 
flutuando conectados nas suas respectivas entidades não é eficiente.
```

Recomendamos representar os atributos dentro do retângulo das entidades, separando apenas o título da entidade dos atributos por uma linha. Abaixo temos uma representação na figura da esquerda a visão lógica e na da direita a visão física, representam a mesma entidade com duas visões diferentes; este mesmo exemplo pode ser utilizado nas situações de modelagem de  classe (visão lógica e física).<br>



<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/logico_fisico.png" alt= “atributos” width="350" height="180">

[Voltar ao sumário](#sumário)<br>







## 2.3. Relacionamentos

A forma como uma entidade se conecta com outra, ou seja, a forma como uma entidade (ou objeto ou "**coisa**") esta associada com outras deve ser representada por uma ligação. Esta ligação é chamada de relacionamento. Basicamente uma relação pode ser representada por uma linha simples, interligando as entidades. <br>

Nota: As entidades devem ter atributos semelhantes (e com tipos de dados semelhantes) para que esta ligação possa ser realizada. Sugerimos leituras sobre as chaves estrangeiras (FK).<br>

```
Observação:
Existem diversas formas de notação, uma delas é pela utilização
de uma figura tipo um diamante no centro da linha que interliga as
entidades, não recomendamos pois esse tipo de abordagem, mais uma 
vez... acaba ocupando uma quantidade grande de espaço conforme o 
modelo vai sendo especializado e ampliado.
```

Na figura abaixo o relacionamento pode ser lido como: 1(um) aluno "**pode ter**" zero ou muitos "**pets**" ou 1 (um) aluno tem nenhum ou mais de um pets. O lado "**nenhum**" (entidade na direita) pode ser visto como circulo vazio, também nesse lado direito as 3 linhas também podem ser chamadas de "**pé de corvo**". Pois um aluno pode ter mais de um pets assim como podem haver alunos com nenhum pets.<br>

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/relacionamentos.png" alt= “relacionamentos” width="450" height="180">


Na figura abaixo temos vários exemplos de relacionamentos e suas notações com a respectiva cardinalidade (quantidade de ocorrências das entidades em cada lado).<br>

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/tipos_relacionamentos.png" alt= “tipos_de_relacionamentos” width="550" height="280">


<br>

Que tal desenha o mais informal possível ? Objetivando apenas representar as entidades e suas relações.<br>

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/entidades2.png" alt= “desenhos_informal” width="280" height="80">

[Voltar ao sumário](#sumário)<br>






---
# 3. DFD


O Diagrama de Fluxo de Dados (DFD) é uma forma de representação das principais funções de um sistema e movimentação de dados entre estas funções, saíde de entidades e arquivos (ou bancos de dados). O DFD foi desenvolvido e popularizado na década de 70, onde ainda era comum a utilização de arquivos para o armazenamento de dados. Os principais desenvolvedores e promotores deste tipo de diagrama são: Edward Yourdon, Larry Constantine, Tom DeMarco, Chris Gane and Trish Sarson.


Os símbolos utilizados pelo DFD são simples e poucos, sendo eles:<br>

| Símbolo    | Descrição |
| -------- | ------- |
| Círculo  | Processo ou função   |
| Retângulo | Entidade externa     |
| Retângulo com a lateral aberta | Arquivo de dados ou banco de dados |
| Seta | Sentido do fluxo de dados, com descrição de dados |
| Retângulo "maior" pontilhado | Opcional, geralmente representa as fronteiras do sistema |

<br>

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/dfd3.png" alt="dfd" style="height: 480px; width:480px;"/>

[Voltar ao sumário](#sumário)<br>







---
# 4. UML

Unified Modeling Language (UML, ou linguagem de modelagem unificada), é um componente da engenharia de software como ferramenta de diagramação e modelagem de sistemas principalmente orientados a objetos. Outros tipos de sistemas como estruturados, real-time também podem ser modelados com UML (apesar de este não ser seu foco principal). A UML é divida em vários diagramas que abordam aspectos dinâmicos e estáricos da visão estrutural de um sistema.  A UML surgiu  na década de 1990 pelo Object Management Group (OMG).



Todos os diagramas da UML são:<br>

A-Diagramas de estrutura (aspecto estático):<br>
* 1-Diagrama de classes<br>
* 2-Diagrama de objetos<br>
* 3-Diagrama de perfil<br>
* 4-Diagrama de componentes<br>
* 5-Diagrama de estruturas compostas<br>
* 6-Diagrama de implantação<br>
* 7-Diagrama de pacotes<br>

B-Diagramas de comportamentos (aspecto dinâmico):<br>
* 8-Diagrama de atividades<br>
* 9-Diagrama de casos de uso<br>
* 10-Diagrama de máquina de estados<br>
* 11-Diagrama de sequência<br>
* 12-Diagrama de comunicação<br>
* 13-Diagrama de visão geral de interação<br>
* 14-Diagrama de tempo<br>


Tipos de diagramas da UML:

```mermaid
flowchart
    A[Diagrama`s] --> B(Diagrama de estrutura)
        B --> B1[Diagrama de classes]
        B --> B2[Diagrama de objetos]
        B --> B3[Diagrama de perfil]
        B --> B4[Diagrama de componentes]
        B --> B5[Diagrama de estruturas compostas]
        B --> B6[Diagrama de implantação]
        B --> B7[Diagrama de pacotes]
    A[Diagramas] --> C(Diagrama de comportamentos)
        C --> C1[Diagrama de atividades]
        C --> C2[Diagrama de casos de uso]
        C --> C3[Diagrama de máquina de estados]
        C --> D[Diagrama de interação]
            D --> D1[Diagrama de sequência]
            D --> D2[Diagrama de comunicação]
            D --> D3[Diagrama de visão geral de interação]
            D --> D4[Diagrama de tempo]
```

[Voltar ao sumário](#sumário)<br>


**Os mais interessantes e populares são os citados a seguir:**

## 4.1. Diagrama de classes

O diagrama de classe são o pilar da UML e dos projetos OO. A classe é um retângulo dividido em 3 partes (nome da classe, atributos(características ou campos) e métodos (procedimentos ou funções)). O diagrama de classes e subclasses são associadas via uma relação (similar ao DER (diagrama entidade relacionemnto)) permitindo apresentar os componentes estáticos de um sistema, esquematizando estruturas de dados poderão ser implementadas na forma de tabelas em um banco e como funções de aplicações.

Exemplos:

<img src="https://github.com/monteiro74/diagramas_resumo/blob/main/imagens/classe1.png" alt="Classe" style="height: 100px; width:100px;"/>

Outro diagrama:

<img src="https://github.com/monteiro74/diagramas_resumo/blob/main/imagens/classe11.png" alt="Classes" style="height: 350px; width:450px;"/>


Note que na figura temos uma associação (ou relação) do tipo generalização (e especialização), representada por um triangulo no início da linha. O conceito de hereditariedade é também representado por este símbolo uma linha com uma seta:

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/classe_generaliza_especializa.png" alt="Herança" style="height: 350px; width:450px;"/>


Alguns símbolos de acesso mais populares (ou modificadores de acesso ou visibilidade):

| Símbolo    | Significado |
| -------- | ------- |
| +  | Público    |
| - | Privado    |
| #    | Protegido    |

Definição: 
* "**Public**: qualquer um pode acessar variáveis de instância públicas.
* **Protected**: apenas métodos do mesmo pacote ou subclasse podem acessar variáveis de instância protegidas.
* **Private**: apenas métodos da mesma classe (excluindo métodos de uma subclasse) podem acessar variáveis de instâncias privadas”. 

Fonte: https://blog.grancursosonline.com.br/java-modificadores-de-acesso-parte-ii-15-questoes-comentadas/#:~:text=public%3A%20qualquer%20um%20pode%20acessar,acessar%20vari%C3%A1veis%20de%20inst%C3%A2ncias%20privadas%E2%80%9D.

Como exemplificado na figura abaixo:<br>

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/classe22.png" alt="Modificador de acesso" style="height: 150px; width:200px;"/>

[Voltar ao sumário](#sumário)<br>







## 4.2. Diagrama de casos de uso

Este diagrama da UML apresente um aspecto dinâmico de um sistema, ou melhor o comportamento do sistema com relação seus atores (sejam eles pessoas ou interações com outros sistemas). Ele apresenta partes funcionais de um sistema. Este diagrama contém atores, ações (ou funções) e fronteiras do sistema modelado. Todo ator é representado por um boneco de linhas simples ou "palitinhos". Este diagrama é foca no comportamento do sistema. Este diagrama não apresenta detalhes internos de funcionamento do sistema. 

O diagrama de casos de uso apresenta relações entre atores, funcionalidades, sistema e subsistemas, independente da ordem em que estas interações ocorrem. O diagrama permite capturar o contexto e os requisitos do sistema. 

Segue um exemplo com as estruturas abaixo:

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/casosdeuso1.png" alt="Modificador de acesso" style="height: 300px; width:380px;"/>

Outro exemplo:

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/casosdeuso2.png" alt="Modificador de acesso" style="height: 450px; width:500px;"/>

Para extender os casos de uso temos duas notações, incluve e extend. No tipo include o caso de uso existe uma adição de uma nova operação no caso de uso base, ou seja no caso include uma nova sub operação é adicionada. Já no caso de extend, uma funcionalidade opcional é adicionado às operações do sistema, ou seja, não é algo obrigatório.

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/casosdeuso3.png" alt="Modificador de acesso" style="height: 250px; width:350px;"/>


[Voltar ao sumário](#sumário)<br>




## 4.3. Diagrama de atividades

São diagramas que representam o estado dinâmico de um sistema, ou seja, representam ações que o sistemas e suas partes executam. Foi incorporado à UML, é também chamado de fluxograma ou flow chart. Este diagrama apresenta atividades em retângulos com cantos arredondados, cada retângulo é uma passo do fluxo. O início de cada fluxo de atividades é representado por um bola preenchida e o fim do fluxo representado por um círculo. Geralmente o diagrama é lido na vertical, sendo o início e o final esta na base do desenho. Este desenho um símbolo de diamante para representar uma decisão ou bifurcação no fluxo indicando uma opção de caminho alternativo. Este diagrama também possibilida que atividades paralelas sejam representadas. Permite que fluxo de processos de negócio sejam identificados. Permite a modelagem de fluxos entre os casos de uso. Atividades complexas podem ser modeladas.


<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/atividades1.png" alt="Modificador de acesso" style="height: 430px; width:330px;"/>

Uma das vantagens desse diagrama é que ele é bem popular além da engenharia de software e dos círculos de análise de sistemas, o fluxograma é um conceito bem difundido, podendo ser usando para representar a lógica de um algoritmo até os passos de uma tarefa administrativa. Pode ser usado por programadores para representar o que ocorre dentro de um caso de uso. Portanto após um caso de uso estar pronto é possível inicial o desenho do diagrama de atividades para documetno métodos, funções ou outras operações do sistema (independente se estas forem manuais ou automatizadas).

[Voltar ao sumário](#sumário)<br>









## 4.4. Diagrama de sequência

São diagramas que apresentam aspectos dinâmicos de um sistema orientados a eventos. Estes diagramas mostram a ordem na qual as colaborações entre as partes ocorrem. É utilizado um eixo vertical para representar uma **timeline** (linha do tempo) enquanto as mensagens são passadas entre objetos. Podem representar as interações do que foi documentado nos diagramas de casos de uso. Podem mostrar interações entre usuários e partes do sistema e partes do sistema entre si. 

Permite que sejam modeladas as colaborações entre instânicas de objetos (que **realiza** um caso de uso). Os objetos são organizados lado a lado e as mensagens que estes trocam entre si são apresentadas abaixo destes em uma ordem do topo para baixo, de direita para esquerda. A mensagem mais acima é a mais antiga e a mais a baixo são as mais atuais. A linha do tempo corre na vertical a partir de cada objeto. A linha do tempo de cada objeto representam também seu **linhas de vida** (ou life line), ou sejam, o momento que o objeto é chamado, faz sua operação e dá um retorno ou aciona outro objeto. As life line são verticais. As linhas entre as linhas de tempo ou linhas de vida são conectadas via mensagens, as mensagens são as linhas horizontais.


<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/diagrama_de_sequencia1.png" alt="Modificador de acesso" style="height: 380px; width:430px;"/>


[Voltar ao sumário](#sumário)<br>


Diagrama de sequência inserido no github usando a biblioteca mermaid:

```mermaid
sequenceDiagram
    Ana->>Bob: Oi Bob, Como estas?
    Bob-->>Ana: Bem!
    Ana-)Bob: Até mais!
```




## 4.5. Diagrama de componentes

O diagrama de componenes é um "desenho" importante no projeto de um software pois apresenta os "órgãos" (ou estruturas) internas do software. Este diagrama apresenta a forma como estão conectados os elementos do software. Um componente pode representar um agrupamento de classes ou uma classe entre sistemas ou subsistemas desde que estes tenham alguma interação entre si. São identificadores apenas componentes necessários para que o sistema funcione. 

Permite representar partes de códigos fontes, pois permite representar as partes funcionais de interesse. Permite representar as peças distribuíveis e/ou substituíveis de um sistema, bem como os pontos de interface do sistema que se deseja representar e seu contato com outros sistemas. É possível representar e agrupar cada função do sistema.

Os elementos representados podem ser vários como:
* biblitecas de funções (ou outros tipos de bibliotecas)
* arquivos de documentação
* executáveis
* arquivos ou tabelas
* formulários (ou telas de usuários)
* relatórios (projeto ou templates de relatórios)
* entre outros elementos que se deseja representar sobre as partes de um sistema e seu interelacionamento.


```
Nota: A UML usa o termo componente para indicar um módulo (de classes) 
que representa um sistema (ou suas sub partes).
```

A partir de diagramas como o diagrama de classes e o diagrama de casos de uso é possível ter conhecimento de vários elementos de um sistema, a representação destes via artefatos de software vem a ter sequência com o diagrama de componentes. Estes elementos podem ser representados da 3 formas:
* Elementos de instalação: o que é necessário para rodar o software como um servidor de banco de dados, bibliotecas .net, etc
* Elementos para o funcionamento: bibliotecas matemáticas, visual c++ redistributable, bibliotecas dinâmicas DLL, arquivos de ajuda, etc.
* Elementos de execução: executáveis e seus arquivos acessórios.

O diagrama de componentes pode ser representado de várias formas, seguem alguns exemplos:


<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/componentes1.png" alt="Componentes do diagrama de componentes" style="height: 160px; width:500px;"/>

Outro exemplo, mostrando um pacote e seus componentes internos (outros pacotes), é uma forma de representação de um empacotamento:


<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/componentes2.png" alt="Componentes do diagrama de componentes" style="height: 160px; width:330px;"/>

[Voltar ao sumário](#sumário)<br>




### 4.5.1. Interfaces

As interfaces representam um serviço, mas não apresentam detalhes de sua implementação. Interface necessária do componente ou esperada (é um semi-círculo) e o a interface fornecida (círculo). Exemplo:

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/componentes3.png" alt="Interfaces" style="height: 90px; width:330px;"/>

A interface fornecida sai do componente a partir de uma linha reta e termina em um circulo fechado, é uma fonte de saída de dados produzidos pelo componente. A interface necessária sai do componente por uma reta e termina em uma lua (semi círculo), é saída que representa a parte do sistema que pede informações.

A representação de porta é feita por um quadrado da qual parte a ligação do círculo:

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/componentes4a.png" alt="Portas" style="height: 90px; width:330px;"/>

[Voltar ao sumário](#sumário)<br>



### 4.5.2. Artefatos

São elementos que representam **entidades físicas** em um sistema de software. Por exemplo:

* documento de texto
* arquivo fonte
* script
* arquivo binário executável
* arquivos
* banco de dados, tabelas, índices

Um exemplo de um diagrama de artefatos:

![Exemplo de artefato](https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/artefato.png)

[Voltar ao sumário](#sumário)<br>

## 4.6. Diagrama de pacotes

O diagrama de pacote é um diagrama estrutural que mostra a organização de vários outros elementos da UML, é um diagrama utilizado para agrupar outros elementos. Um pacote contém um grupo de elementos de diagramas relacionados. Estes tippos de elementos podem ser vários tipos como:

* Outros diagramas (um diagrama de classe pode estar contigo em um diagrama de pacote, diagramas de casos de uso, etc)
* Documentação, anotações, artefatos de documentação em geral
* Classes
* outros diagramas de pacotes (um diagrama de pacote pode conter outro diagrama de pacote)
* Outros elementos que sejam necessários para a documentação do sistema

A representação de um pacote é um ícone frequentemente utilizado para representar uma pasta em um sistema de arquivos. Permitem que a relação entre os elementos possam ser representadas. Diagramas de classes podem ter classes que trabalham em conjunto agrupas via diagrama de pacotes. Na programa de um sistema um pacote pode ser visto com um namaspace pois contém vários elementos que um sistema deve conhecer.

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/pacote1.png" alt="Pacote" style="height: 80px; width:100px;"/>

Outro exemplo:

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/pacotes2.png" alt="Pacotes" style="height: 250px; width:400px;"/>

Outro exemplo:

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/pacotes3.png" alt="Pacotes" style="height: 180px; width:400px;"/>


Neste exemplo a ligação importa permite que um pacote importe funcionalidades de outro, no outro exemplo, acesso significar que um pacote necessita de ajuda de outro pacote.

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/pacotes4.png" alt="Pacotes" style="height: 170px; width:380px;"/>

[Voltar ao sumário](#sumário)<br>










## 4.7. Diagrama de implantação

O diagrama de implantação (ou Deployment diagram) é uma modelagem física dos componentes do sistema sobre os nós necessários para sua execução. Os nós aparecem como caixas (ou cubos) e cada artefato de software que irá funcionar dentro do nó recebe um retângulo. Um nó pode ter muitos artefatos no seu interior. Este diagrama mostra onde o sistema irá ser implantado (fisicamente), ou seja, qual é a arquitetura de execução. 

Os nós podem abstrair vários elementos físicos como processador, dispositivos, memória, etc. Os nós podem possuir estados e representar uma determinado valor ou uma condição especial de execução do sistema. Os artefatos de software são alocados dentro dos nós. Nós também podem receber informações sobre números IPs, rede, DMS, etc.

Os diagramas de implantação também podem representar a topologia da rede, ou seja, a representação geográfica dos computadores necessários para operar o sistema. Apresentam os nós que são necessário em **run time**. 

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/deploy1.png" alt="Implementacao" style="height: 220px; width:450px;"/>


[Voltar ao sumário](#sumário)<br>




---
# 5. Fundamental Modeling Concepts (FMC)

Site sobre FMC: http://www.fmc-modeling.org/home


```
Observação: Não recomendo FMC no momento !
```

[Voltar ao sumário](#sumário)<br>


---
# 6. Criando diagramas em páginas do github:

Exemplos de diagramas criado diretamente com markdown.

Todos os exemplos abaixo foram adaptados das seguintes fontes:
* https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/
* https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams
* https://support.typora.io/Draw-Diagrams-With-Markdown/
* https://mermaid.js.org/intro/
* https://gist.github.com/blackcater/1701e845a963216541591106c1bb9d3b

Outros exemplos:

* https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams
* https://support.typora.io/Draw-Diagrams-With-Markdown/

Exemplo 1:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

Exemplo 2:

```mermaid
---
title: Exemplo de diagrama Git
---
gitGraph
   commit
   commit
   branch develop
   checkout develop
   commit
   commit
   checkout main
   merge develop
   commit
   commit
```

Exemplo 3:

```mermaid
stateDiagram
    [*] --> Primeiro
    state Primeiro {
        [*] --> segundo
        segundo --> [*]
    }
```

Exemplo 4:

```mermaid
gitGraph
       commit id: "Alpha"
       commit id: "Beta"
       commit id: "Gamma"
```

Outras formas de montar diagramas dentro de páginas markdown:
https://github.com/JakeSteam/Mermaid/blob/main/entity-relationship.md


---
# 7. BPMN

Significa Business Process Model and Notation (notação para modelagem de processo de negócios). É um padrão para modelagem de processos de negócios. Permitem que os colaboradores envolvidos possa visualizar o processo como um todo via uma representação visual/gráfica similar ao um fluxograma. É um diagrama representado por uma sequência de passos a partir de um início até um fim. Cada etapa é representada por um retângulo (com pontas arredondadas). O BPMN não faz parte da UML. Mas podem ser utilizados em conjunto para representar diferentes aspectos de um processo de negócio. Um DFD pode ser parecido com um BPMN, porém os DFD possuem 4 elementos como processo, fluxo, armazenamento e entidade externo), já  anotação BPMN permite que se usem diversos fluxo e elementos.

| Símbolo    | Descrição |
| -------- | ------- |
| Círculo simples  | Início do processo   |
| Retângulo com bordas arredondadas| Atividade, o que deve ser executado no processo     |
| Círculo com bola preta | Fim do processo |
| Losângulo | Decisão, bifurcação do processo |
| Losângulo com cruz | bifurcação em paralelo |
| Swimlane ou raia | São raias horizontais que representam a função ou papel que executa aquela atividade do processo |
| linha com seta de ponta preta | Indica o fluxo de execução do processo, é o sentido que o processo anda |


Exemplo:

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/BPMN.jpg" alt="Pacote" style="height: 472px; width:682px;"/>


[Página oficial da notação BPMN](https://www.omg.org/spec/BPMN/2.0/)

[Voltar ao sumário](#sumário)<br>



---
# 8. Referências


Fonte sobre BPMN https://www.omg.org/spec/BPMN/2.0/

Fonte sobre UML https://www.uml.org/

Diagramas dentro de arquivos markdown https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/ e https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams


[Voltar ao sumário](#sumário)<br>

---
# 9. Como citar esta página em seus trabalhos, artigos ou outras referências:

## 9.1. Citação bibliográfica:

```
Monteiro, Emiliano, (2023). Breve resumo de diagramas. Github. [Computer Software] https://github.com/monteiro74/diagramas_resumo. 
```

## 9.2. Citação bibtex para Latex:

```
@misc{Monteiro2023,
  author = {Emiliano Monteiro},
  title = {Breve resumo de diagramas},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/monteiro74/diagramas_resumo}},
  Notes = {Computer Software},
}
```

---
# 10. Lista de ferramentas

Lista de ferramentas para serem usados conforme o caso:

https://github.com/monteiro74/lista_de_ferramentas#5-IDEs






---
# 11. Comentários finais 


```
Critérios para os diagramas entrar nesta lista:
1. São materiais de suporte ao projeto e desenvolvimento de sistemas e bancos de dados.
2. Material foi ou poderá ser usado em sala de aula.
3. Em alguns diagramas foram utilizados os exemplos da 
biblioteca [Mermaid](https://mermaid.js.org/intro/), para inserir desenho nesta página github.
```

[Voltar ao sumário](#sumário)<br>

---
# 12. Avisos, licença, estatísticas...


## 12.1. Avisos
```
As informações aqui contidas podem ser alteradas sem aviso prévio.
Primeira postagem em: 17/jun/2023. 
Última atualização em: 24/agosto/2023.
Se desejar conhecer outras ferramentas para desenvolvimento de software, consulte a página: https://github.com/monteiro74/lista_de_ferramentas#5-IDEs
```

[Voltar ao sumário](#sumário)<br>


## 12.2. Licença

```
Autor: Prof. Dr. Monteiro.
Licença: Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) 
https://creativecommons.org/licenses/by-nc-sa/4.0/

```


[Voltar ao sumário](#sumário)<br>





---
## 12.3. Estatísticas do repositórios do Prof. Monteiro<br>

[![teste](https://github-readme-activity-graph.vercel.app/graph?username=monteiro74&theme=github-compact)](https://github.com/monteiro74/diagramas_resumo)


[![GitHub Streak](https://streak-stats.demolab.com/?user=monteiro74&theme=dark)](https://git.io/streak-stats)


[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=monteiro74)](https://github.com/monteiro74/github-readme-stats)



Pulse:<br>
https://github.com/monteiro74/diagramas_resumo/pulse<BR>

Contribuições de:<br>
<a href="https://github.com/monteiro74/diagramas_resumo/contributors">
  <img src="https://contrib.rocks/image?repo=monteiro74/diagramas_resumo" />
</a>

Histórico de frequência de código:<BR>
https://github.com/monteiro74/diagramas_resumo/graphs/code-frequency<BR>

Atividade de commits:<BR>
https://github.com/monteiro74/diagramas_resumo/graphs/commit-activity<BR>

Trafego:<BR>
https://github.com/monteiro74/diagramas_resumo/graphs/traffic<BR>


![stats](https://github-readme-stats.vercel.app/api?username=monteiro74&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage)

![stats](https://github-readme-stats.vercel.app/api?username=monteiro74&show_icons=true&theme=dark)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=monteiro74)](https://github.com/monteiro74/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=monteiro74&layout=donut-vertical)](https://github.com/monteiro74/github-readme-stats)


[Voltar ao sumário](#sumário)<br>



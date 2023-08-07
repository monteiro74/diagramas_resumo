# Breve resumo de diagramas

Uma breve compilação de material (curadoria de conteúdo digital) sobre diversos diagramas utilizados na disciplina de engenharia de software, projeto de software, arquitetura de sistemas e bancos de dados. "Resumo dos diagramas mais comuns" que usamos nestas disciplinas. Este não é um guia definitivo, mas um pequeno tutorial compilado para auxiliar alunos e devs.


# Conteúdo:

[1 Definições](#1-Definições) <br>
[2 DER - Diagrama Entidade Relacionamento](#2-DER) <br>
[3 DFD - Diagrama de Fluxo de Dados](#3-DFD) <br>
[4 UML - Unified Modeling Language](#4-UML) <br>
[5 BPMN - Business Process Model and Notation](#5-BPMN) <br>
[5 Gantt](#6-gantt)<br>
[Referências](#Referências) <br>


<!---


     comentario 0
     ![Nova lei de licitação](https://raw.githubusercontent.com/monteiro74/lab_inova_serv_pub/main/imagens/nova_lei_licitacao.jpeg)


```
exemplo de caixa de texto
```

-->





---
# 1 Definições

Um diagrama é um desenho mostrando um estrutura ou representação esquemática de algo (como uma máquina ou sistema), de forma a apresentar simplificadamente sua estrutura e/ou funcionamento. <br>

Definição 1: Diagrama é uma representação gráfica usada para demonstrar um esquema simplificado ou um resumo sobre um assunto. <br>
Fonte: https://www.significados.com.br/diagrama/

Definição 2: O diagrama é um gráfico que apresenta informação de forma esquematizada e relacionada a algum tipo de área, seja na política ou economia de algum país ou empresa, e que aparece representada numericamente e em forma de tabela.<br>
Fonte: https://conceitos.com/diagrama/

Definição 3: Delineação; modo de representação feito através de gráficos, de esquemas, de linhas, de pontos: diagrama elétrico. Esboço; demonstração dos aspectos gerais de alguma coisa: diagrama do televisor. Tipo de maquete que contém o cenário usado nas filmagens. <br>
Fonte: https://www.dicio.com.br/diagrama/







---
# 2 DER

É um tipo de diagrama que apresenta as entidades de um sistema; estas entidades são conectadas por relacionamentos, as entidades possuem internamente atributos. Este diagrama é utilizado para modelar bancos de dados, também pode representar regras de negócio utilizadas pelas empresas. Também permite perceber as conexões lógicas entre "as coisas" com as quais se deseja representar informações. O criado deste diagrama é o Professor Peter Chen ([Peter Pin-Shan Chen](https://en.wikipedia.org/wiki/Peter_Chen)) na década de 1970 naSloan School of Management no MIT publicado em “The Entity-Relationship Model: Toward a Unified View of Data". O trabalho de DER contribuiu para o modelo de Classes e posteriormente com a UML. 

São componentes de um DER: entidades, atributos e relacionamentos. Os diagramas entidade relacionamento também proporcionam um meio de comunicação. Os diagramas entidades relacionamento são também chamados de diagram ER, Modelo ER. São diagramas estruturais utilizados principalmente para o projeto de um banco de dados (relacional e/ou objeto relacional) 


<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/der.png" alt= “DER” width="350" height="180">




## 2.1 Entidade


As entidades são "as coisas" que queremos representar e guardar informações sobre. São exemplos de entidades carros, objetos, lugares, pessoas, veículos, etc. As entidades são representadas por um retângulo com seu nome no centro. 


![Exemplo de entidades](https://github.com/monteiro74/diagramas_resumo/blob/main/imagens/entidades.jpg?raw=true "Exemplo de entidades")








## 2.2 Atributos

Os atributos dão características das entidades. São os elementos básicos que ajudam a formar e dar identidade às entidades. São os tijolos básicos das entidades e sua compreensão. Atributos também podem ser características de relações. 

```
Observação:
Algumas ferramentas de diagramação os atributos estão conectados nas
entidades e representados em forma oval. É bom citar que esta é uma das
piores formas de representação de atributos em entidades, pois os diagramas
tendem a crescer conforme o analista vai melhorando ou especificando mais
detalhes nos diagramas, essa abordagem de usar  balões como atributos 
flutuando conectados nas suas respectivas entidades não é eficiente.
```

Recomendamos representar os atributos dentro do retângulo das entidades, separando apenas o título da entidade dos atributos por uma linha. Abaixo temos uma representação na figura da esquerda a visão lógica e na da direita a visão física, representam a mesma entidade com duas visões diferentes; este mesmo exemplo pode ser utilizado nas situações de modelagem de  classe (visão lógica e física).

<!---
![Exemplo de entidades](https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/logico_fisico.png "Exemplo de entidades")
-->


<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/logico_fisico.png" alt= “atributos” width="350" height="180">







## 2.3 Relacionamentos

A forma como uma entidade se conecta com outra, ou seja, a forma como uma entidade (ou objeto ou "coisa") esta associada com outras deve ser representada por uma ligação. Esta ligação é chamada de relacionamento. Basicamente uma relação pode ser representada por uma linha simples, interligando as entidades. 

Nota: As entidades devem ter atributos semelhantes (e com tipos de dados semelhantes) para que esta ligação possa ser realizada. Sugerimos leituras sobre as chaves estrangeiras (FK).

```
Observação:
Existem diversas formas de notação, uma delas é pela utilização
de uma figura tipo um diamante no centro da linha que interliga as
entidades, não recomendamos pois esse tipo de abordagem, mais uma 
vez... acaba ocupando uma quantidade grande de espaço conforme o 
modelo vai sendo especializado e ampliado.
```

Na figura abaixo o relacionamento pode ser lido como: 1(um) aluno "pode ter" zero ou muitos "pets" ou 1 (um) aluno tem nenhum ou mais de um pets. O lado "nenhum" (entidade na direita) pode ser visto como circulo vazio, também nesse lado direito as 3 linhas também podem ser chamadas de "pé de corvo". Pois um aluno pode ter mais de um pets assim como podem haver alunos com nenhum pets.

<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/relacionamentos.png" alt= “relacionamentos” width="450" height="180">







---
# 3 DFD


O diagrama de fluxo de dados é uma forma de representação das principais funções de um sistema e movimentação de dados entre estas funções, saíde de entidades e arquivos (ou bancos de dados). O DFD foi desenvolvido e popularizado na década de 70, onde ainda era comum a utilização de arquivos para o armazenamento de dados. Os principais desenvolvedores e promotores deste tipo de diagrama são: Edward Yourdon, Larry Constantine, Tom DeMarco, Chris Gane and Trish Sarson.


Os símbolos utilizados pelo DFD são simples e poucos, sendo eles:<br>

| Símbolo    | Descrição |
| -------- | ------- |
| Círculo  | Processo ou função   |
| Retângulo | Entidade externa     |
| Retângulo com a lateral aberta | Arquivo de dados ou banco de dados |
| Seta | Sentido do fluxo de dados, com descrição de dados |
| Retângulo "maior" | Opcional, geralmente representa as fronteiras do sistema |

<br>


<img src="https://raw.githubusercontent.com/monteiro74/diagramas_resumo/main/imagens/dfd2.png" alt= “relacionamentos” width="450" height="400">

---
# 4 UML

Página em construção... 



Todos os diagramas da UML:<br>

A-Diagrama de estrutura:<br>
* 1-Diagrama de classes<br>
* 2-Diagrama de objetos<br>
* 3-Diagrama de perfil<br>
* 4-Diagrama de componentes<br>
* 5-Diagrama de estruturas compostas<br>
* 6-Diagrama de implantação<br>
* 7-Diagrama de pacotes<br>

B-Diagrama de comportamentos:<br>
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


### 4.1 Diagrama de classes

Definição

Exemplos:

![Exemplo de classe](https://github.com/monteiro74/diagramas_resumo/blob/main/imagens/classe1.png)


## Fundamental Modeling Concepts (FMC)

http://www.fmc-modeling.org/home


```
Dica: não recomendo FMC !
```


---
# 5 BPMN

Página em construção...






---
# 6 Gantt


Página em construção...





---
# Referências recomendadas









---
## Comentários finais 


```
Critérios para os diagramas entrar nesta lista:
1. São materiais de suporte ao projeto e desenvolvimento de sistemas e bancos de dados.
2. Material foi ou poderá ser usado em sala de aula.
```



---
# Avisos, licença, observações, estatísticas



```
As informações aqui contidas podem ser alteradas sem aviso prévio.
Primeira postagem em: 17/jun/2023. 
Última atualização em: 06/agosto/2023.
Se desejar conhecer outras ferramentas para desenvolvimento de software, consulte a página: https://github.com/monteiro74/lista_de_ferramentas#5-IDEs
```
Lista de ferramentas: https://github.com/monteiro74/lista_de_ferramentas#5-IDEs


```
Autor: Prof. Dr. Monteiro.
Licença: Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) 
https://creativecommons.org/licenses/by-nc-sa/4.0/

```

Histórico de atualizações nos repositórios do Prof. Monteiro:<br>
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

[Voltar ao sumário](#conteúdo)<br>


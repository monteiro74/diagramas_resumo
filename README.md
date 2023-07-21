# Breve resumo de diagramas

Uma breve compilação de material (curadoria de conteúdo digital) sobre diversos diagramas utilizados na disciplina de engenharia de software, projeto de software, arquitetura de sistemas e bancos de dados. "Resumo dos diagramas mais comuns" que usamos nestas disciplinas. Este não é um guia definitivo, mas um pequeno tutorial compilado para auxiliar alunos e devs.


# Conteúdo:

[1 Definições](#1-Definições) <br>
[2 DER - Diagrama Entidade Relacionamento](#2-DER) <br>
[3 DFD - Diagrama de Fluxo de Dados](#3-DFD) <br>
[4 UML - Unified Modeling Language](#4-UML) <br>
[5 BPMN - Business Process Model and Notation](#5-BPMN) <br>
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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque auctor ante id ipsum sollicitudin imperdiet vel nec arcu. 

## 2.1 Entidade

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque auctor ante id ipsum sollicitudin imperdiet vel nec arcu. 

## 2.2 Atributos

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque auctor ante id ipsum sollicitudin imperdiet vel nec arcu. 

## 2.3 Relacionamentos

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque auctor ante id ipsum sollicitudin imperdiet vel nec arcu. 





```
Dica: exemplo de caixa de texto
```

---
# 3 DFD

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque auctor ante id ipsum sollicitudin imperdiet vel nec arcu. Maecenas vitae neque non orci lobortis condimentum. Vivamus luctus massa velit, eu mattis tortor porttitor vitae. Quisque posuere nibh nec ornare volutpat. Vivamus id arcu suscipit, convallis odio vel, vehicula nisi. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nam hendrerit quis diam consectetur pulvinar. Morbi bibendum sagittis sapien, quis efficitur velit iaculis et. Nunc eu arcu et dolor dignissim placerat sed et eros. Vivamus viverra nunc lacus, sit amet porttitor metus tempor et. Proin lectus orci, aliquet et orci nec, rutrum euismod enim. Praesent accumsan nibh quam, eu efficitur mauris convallis dignissim. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut blandit, velit vitae lobortis iaculis, mauris urna lacinia ante, quis viverra nisi libero fermentum dolor.

Comparativo:

|	          | CPSI          | Contrato de fornecimento|
| ------------ | ------------- | ----------------------- |
| Tempo        | 12 meses + 12 | 24 meses + 24           |
| Valor        | 1,6           | 8                       |

```
Dica: exemplo de caixa de texto
```

---
# 4 UML

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque auctor ante id ipsum sollicitudin imperdiet vel nec arcu. Maecenas vitae neque non orci lobortis condimentum. Vivamus luctus massa velit, eu mattis tortor porttitor vitae. Quisque posuere nibh nec ornare volutpat. Vivamus id arcu suscipit, convallis odio vel, vehicula nisi. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nam hendrerit quis diam consectetur pulvinar. Morbi bibendum sagittis sapien, quis efficitur velit iaculis et. Nunc eu arcu et dolor dignissim placerat sed et eros. Vivamus viverra nunc lacus, sit amet porttitor metus tempor et. Proin lectus orci, aliquet et orci nec, rutrum euismod enim. Praesent accumsan nibh quam, eu efficitur mauris convallis dignissim. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut blandit, velit vitae lobortis iaculis, mauris urna lacinia ante, quis viverra nisi libero fermentum dolor.



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

![Exemplo de classe](https://github.com/monteiro74/diagramas_resumo/blob/main/imagens/classe1.png "Exemplo de classe")


## Fundamental Modeling Concepts (FMC)

http://www.fmc-modeling.org/home


```
Dica: não recomendo FMC !
```


---
# 5 BPMN

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque auctor ante id ipsum sollicitudin imperdiet vel nec arcu. Maecenas vitae neque non orci lobortis condimentum. Vivamus luctus massa velit, eu mattis tortor porttitor vitae. Quisque posuere nibh nec ornare volutpat. Vivamus id arcu suscipit, convallis odio vel, vehicula nisi. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nam hendrerit quis diam consectetur pulvinar. Morbi bibendum sagittis sapien, quis efficitur velit iaculis et. Nunc eu arcu et dolor dignissim placerat sed et eros. Vivamus viverra nunc lacus, sit amet porttitor metus tempor et. Proin lectus orci, aliquet et orci nec, rutrum euismod enim. Praesent accumsan nibh quam, eu efficitur mauris convallis dignissim. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut blandit, velit vitae lobortis iaculis, mauris urna lacinia ante, quis viverra nisi libero fermentum dolor.


Comparativo:

|	          | CPSI          | Contrato de fornecimento|
| ------------ | ------------- | ----------------------- |
| Tempo        | 12 meses + 12 | 24 meses + 24           |
| Valor        | 1,6           | 8                       |

---
# Referências

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque auctor ante id ipsum sollicitudin imperdiet vel nec arcu. Maecenas vitae neque non orci lobortis condimentum. Vivamus luctus massa velit, eu mattis tortor porttitor vitae. Quisque posuere nibh nec ornare volutpat. Vivamus id arcu suscipit, convallis odio vel, vehicula nisi. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nam hendrerit quis diam consectetur pulvinar. Morbi bibendum sagittis sapien, quis efficitur velit iaculis et. Nunc eu arcu et dolor dignissim placerat sed et eros. Vivamus viverra nunc lacus, sit amet porttitor metus tempor et. Proin lectus orci, aliquet et orci nec, rutrum euismod enim. Praesent accumsan nibh quam, eu efficitur mauris convallis dignissim. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut blandit, velit vitae lobortis iaculis, mauris urna lacinia ante, quis viverra nisi libero fermentum dolor.


---
# Comentários finais 


```
Critérios para os diagramas entrar nesta lista:
1. São materiais de suporte ao projeto e desenvolvimento de sistemas e bancos de dados.
2. Material foi ou poderá ser usado em sala de aula.
```


```
As informações aqui contidas podem ser alteradas sem aviso prévio.
Primeira postagem em: Maio/2023. 
Última atualização em: 20/julho/2023.
Se desejar conhecer outras ferramentas para desenvolvimento de software, consulte a página: https://github.com/monteiro74/lista_de_ferramentas#5-IDEs
```
Lista de ferramentas: https://github.com/monteiro74/lista_de_ferramentas#5-IDEs


```
Autor: Prof. Dr. Monteiro.
Licença: Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) 
https://creativecommons.org/licenses/by-nc-sa/4.0/

```
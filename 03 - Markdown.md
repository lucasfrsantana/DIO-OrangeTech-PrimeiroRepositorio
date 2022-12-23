# **MARKDOWN**

Neste bloco de anotações, iremos abordar sobre os comandos do Markdown. Aqui há uma lista objetiva do comando e sua respectiva função. O site utilizado como base para este texto foi o https://www.markdownguide.org/, https://daringfireball.net/projects/markdown/, https://docs.github.com/pt/ e https://markdown.net.br/.

***

## Sintaxe Básica

### 1. Títulos

Para criar um título, basta usar o sinal "#" no início da palavra ou frase. Conforme a quantidade de hashtags cresce (de 01 a 06), a fonte diminui. Vejamos:

### a) Título Nível 1
 Digitando: # ABCDEFG...
 
 Temos:
# ABCDEFG...


### b) Título Nível 2
 Digitando: ## ABCDEFG...
 
 Temos:
## ABCDEFG...

### c) Título Nível 3
 Digitando: ### ABCDEFG...
 
 Temos:
### ABCDEFG...

### d) Título Nível 4
 Digitando: #### ABCDEFG...
 
 Temos:
#### ABCDEFG...

### e) Título Nível 5
 Digitando: ##### ABCDEFG...
 
 Temos:
##### ABCDEFG...

### f) Título Nível 6
 Digitando: ## ABCDEFG...
 
 Temos:
###### ABCDEFG...

***

### 2. Parágrafos

Para criar um parágrafo, basta deixar uma linha vazia entre os textos, logo gerará um espaço em branco entre eles. Assim:

Digitando "abcdefg...", dando "enter", pulamos para a linha logo abaixo; como queremos que essa linha fique vazia, damos "enter" novamente, e na linha atual digitamos "123456...". Obtemos assim:

    abcdefg...
    
    123456...


Obs.: para destacar o texto, foi usado um TAB antes de digitar "abcdefg...", e seguimos esse alinhamento até o "123456...".

***

### 3. Ênfase

* #### Negrito 
   
  Basta digitarmos o texto entre duplos asteriscos (\*\*texto\*\*):
   
   **ABCDEFG...**, **abcdefg...** **1234567890**
   
* #### Itálico

  Basta digitarmos o texto entre asteriscos (\*texto\*) ou entre underscore (\_texto\_):
  
  *ABCDEFG...*, *abcdefg...*, *1234567890* 

  
* #### Tachado

  Basta digitarmos o texto entre duplos tis (\~\~texto\~\~):
  
  ~~ABCDEFG...~~, ~~abcdefg~~, ~~1234567890~~
  
* #### Negrito e parte em Itálico

  Basta digitarmos o texto entre duplos asteriscos e na parte em que se queira o itálico usar o underscore (\*\*Aqui se \_digita\_ o texto\*\*):
  
  **Aqui se _digita_ o texto**; 
  
  **A casa de _Mariana_ é azul, a de _Flora_ é amarela.**
  
* #### Tudo em Negrito e Itálico

  Basta digitarmos o texto entre triplos asteriscos (\*\*\*texto\*\*\*):
  
  ***ABCDEFG...***, ***abcedfg...***, ***1234567890***
  
* #### Sobrescrito

  Basta digitarmos o texto entre \<sup\> e \</sup\>:
  
  a<sup>1</sup>, a<sup>2</sup>, a<sup>3</sup>...
  
  b<sup>1</sup>, b<sup>2</sup>, b<sup>3</sup>...
  
* #### Subscrito

  Basta digitarmos o texto entre \<sub\> e \</sub\>:
  
  a<sub>1</sub>, a<sub>2</sub>, a<sub>3</sub>...
  
  b<sub>1</sub>, b<sub>2</sub>, b<sub>3</sub>...

***

### 4. Citações

Para criar citações, usamos o símbolo "maior que" (>) antes do texto:

\> Na casa de Maria há muitas flores 
> Na casa de Maria há muitas flores!

É possível fazer citações aninhadas, para isso fazemos uma cadeia com o "maior que":

\> João estava lendo o texto que dizia:  
\>  
\>> Viva o presente, mas pense no futuro.

> João estava lendo o texto que dizia:  
>  
>> Viva o presente, mas pense no futuro.

***

### 5. Listas

Para criarmos listas **ordenadas**, basta que adicionemos os números seguidos de pontos:

1. Primeiro item
2. Segundo item
   1. Sub item
3. Terceiro item

Para criarmos listas **não ordenadas**, basta adicionarmos traços, asteriscos ou sinais de mais para cada item:

- (-) Primeiro item
* (*) Segundo item
+ (+) Terceiro item

**Observação 1**: o sinal usado em cada linha está entre parêntesis, porém o melhor é que se utilize o mesmo sinal desde o início.

**Observação 2**: se o início do item for um número seguido de um ponto, basta usarmos uma barra invertida ( \) para que continuemos a ter uma lista não ordenada.

**Observação 3**: para criarmos um parágrafo entre itens da lista, basta recuarmos o elemento quatro espaços ou uma tabulação (Tab).

***

### 5. Código

Para que uma palavra ou frase seja marcada como código, basta que a coloquemos entre crases (`):

Alguns comandos básicos do Git são: `git status` e `git add`

***

### 6. Réguas Horizontais

Uma régua horizontal é criada quanto temos três ou mais asteriscos, hífens ou sublinhados sozinhos numa linha (como veremos logo abaixo, pois temos usado para separar cada tópico).

***

### 7. Links

Para criar um link, basta colocarmos o texto entre colchetes e depois o URL do site:

    [Google] (www.google.com.br)

**Saída**: [Google](www.google.com.br)


Se quiser colocar uma legenda para quando o mouse passar por sobre o link, basta que coloquemos a legenda entre aspas após o link dentro do parênteses:

    [Google] (www.google.com.br "O site mais usado para buscas")

**Saída**: [Google](www.google.com.br "O site mais usado para buscas")

Se quisermos adicionar o URL de modo mais rápido, basta colocarmos o link entre colchetes angulares:

    <https://www.google.com.br>
    <fake@exemplo.com>
    
**Saída**: 
 
<https://www.google.com.br>
 
<fake@exemplo.com>
 
**Observação 1**: para enfatizarmos os links, podemos usar os códigos de ênfase já vistos anteriormente.

**Observação 2**: se quisermos desativar a vinculação automática de URL, basta colocarmos o link entre crases.


#### Links de Estilo de Referência

Através dessa sintaxe é possível transformar um texto em link com uma referência.

##### - Primeira Parte

Inicialmente, criamos dois conjuntos de colchetes. No primeiro, colocamos o texto do link, o texto que irá aparecer na página; no segundo, colocaremos o rótulo que irá servir de referência para o endereço do link:

Para a primeira parte, temos:

    [Google - Wikipedia][1]

Para a segunda parte, temos:

1. O rótulo, entre colchetes, seguido de dois pontos (:) e seguido de um espaço;
2. A URL do link (pode ser colocado entre colchetes angulares);
3. O título opcional do link (que fica entre aspas).

Por exemplo:

    [1]: https://pt.wikipedia.org/wiki/Google

Agora juntamos todas as partes:

    Para saber mais você pode consultar esse artigo: [Google](https://pt.wikipedia.org/wiki/Google "Google - Wikipedia")

**Saída**: 

Para saber mais você pode consultar esse artigo: [Google](https://pt.wikipedia.org/wiki/Google "Google - Wikipedia")

### 8. Imagens

Para adicionarmos imagem, usamos um ponto de exclamação (!), depois um texto alternativo da imagem entre colchetes, em seguida colocamos o endereço completo da imagem entre parênteses e o título opcional entre aspas dentro do parênteses. Exemplo:

    ![O Google é muito utilizado para buscas](https://pt.wikipedia.org/wiki/Google "Logo do Google")
    
**Saída**:

 ![O Google é muito utilizado para buscas](https://www.google.com.br/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Logo do Google")
 
#### Imagens e Links

Para adicionarmos uma imagem como link, basta criarmos uma formatação de link e no primeiro par de colchetes, onde fazemos referência ao texto, usarmos a formatação para imagem. Exemplo:

    [![A logo do Google](https://www.google.com.br/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](https://pt.wikipedia.org/wiki/Google)
    
**Saída**:

[![A logo do Google](https://www.google.com.br/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](https://pt.wikipedia.org/wiki/Google)

***

### 9. Caracteres de Escape

Quando queremos exibir um caractere literal, basta colocarmos uma barra invertida ( \ ) na frente do caractere. Por exemplo:

    \*\*Sem a barra invertida, este texto estaria em negrito.\*\*
    
    Observe a diferença:
    
    **Sem a barra invertida, este texto estaria em negrito.**
    
 **Saída**:
    
  \*\*Sem a barra invertida, este texto estaria em negrito.\*\*
  
  Observe a diferença:
  
  **Sem a barra invertida, este texto estaria em negrito.**

***

### 10. HTML e Markdown

Quem já possui experiência com HTML, pode mesclar as duas sintaxes no mesmo documento, já que HTML se torna útil em modificar a cor do documento, o tamanho etc. Exemplo:

    Essa **palavra** está em negrito. Esta <em>palavra</em> está em itálico.

**Saída**: 

Essa **palavra** está em negrito. Esta <em>palavra</em> está em itálico.

***
***

## Sintaxe Estendida

### 1. Tabelas

Para criarmos tabelas, usamos traço (-) e barra vertical (|), separando as linhas e colunas. A primeira linha sempre é o cabeçalho da tabela, separando a linha seguinte através de três ou mais traços. Já a separação das colunas é feita pelas barras verticais. Exemplo:

    |Título|Título|
    |------|------|
    |Texto |Texto |
    |Texto |Texto |
    
**Saída**:

|Título|Título|
|------|------|
|Texto |Texto |
|Texto |Texto |

#### Alinhamento

Para alinharmos à esquerda, basta colocarmos dois pontos (:) antes dos traços que separam a linha do cabeçalho. Exemplo:

    | Nome    | Doce      | Cores    |
    | :---    | :----     | :---     |
    | Marcos  | Goiabada  | Vermelho |
    | Beatriz | Chocolate | Amarelo  |

**Saída**:

| Nome    | Doce      | Cores    |
| :---    | :----     | :---     |
| Marcos  | Goiabada  | Vermelho |
| Beatriz | Chocolate | Amarelo  |

Para alinharmos à direita, basta colocarmos dois pontos (:) depois dos traços que separam a linha do cabeçalho. Exemplo:

    | Nome    | Doce      | Cores    |
    | ---:    | ----:     | ---:     |
    | Marcos  | Goiabada  | Vermelho |
    | Beatriz | Chocolate | Amarelo  |

**Saída**:

| Nome    | Doce      | Cores    |
| ---:    | ----:     | ---:     |
| Marcos  | Goiabada  | Vermelho |
| Beatriz | Chocolate | Amarelo  |

Para alinharmos ao centro, basta colocarmos dois pontos (:) antes e depois dos traços que separam a linha do cabeçalho. Exemplo:

    |  Nome    | Doce       | Cores    |
    | :---:    | :----:     | :---:    |
    | Marcos   | Goiabada   | Vermelho |
    | Beatriz  | Chocolate  | Amarelo  |

**Saída**:

|  Nome    | Doce       | Cores    |
| :---:    | :----:     | :---:    |
| Marcos   | Goiabada   | Vermelho |
| Beatriz  | Chocolate  | Amarelo  |

Podemos mesclar a formatação. Exemplo:

    |  Nome    | Doce       | Cores    |
    | :---     | :----:     |  ---:    |
    | Marcos   | Goiabada   | Vermelho |
    | Beatriz  | Chocolate  | Amarelo  |
    
**Saída**:

|  Nome    | Doce       | Cores    |
| :---:    | :----:     | :---:    |
| Marcos   | Goiabada   | Vermelho |
| Beatriz  | Chocolate  | Amarelo  |

Dentro das tabelas, podemos usar os códigos de ênfase, e também podemos usar a barra invertida, para caracteres de escape. Entretanto, se o caractere for a barra vertical, é preciso usar o código HTML `&#124`, que corresponde à barra vertical.

***

### 2. Tachado

Para riscar as palavras com uma linha horizontal ao centro, o que chamamos de *tachar* as palavras, basta colocarmos o texto entre dois símbolos de til:

    Eu ~~não~~ irei vencer esse obstáculo!
   
Saída:

Eu ~~não~~ irei vencer esse obstáculo!

***

### 3. Emojis

Há duas formas de adicionar emojis: copiando e colando, ou digitando os códigos de acesso de emoji.

- #### Copiando e Colando Emojis

Basta copiar um emoji de alguma fonte ([Emojis do Piliapp](https://pt.piliapp.com/symbol/), [Emojipedia](https://emojipedia.org/pt/fonte/), [Emojiterra](https://emojiterra.com/pt/) etc) e colar no documento.

- #### Digitando Códigos

Em alguns aplicativos Markdown é permitido que se insira emojis através de códigos. Estes começam com dois pontos (:) e o nome do emoji. Por exemplo:

    Feliz Aniversário! :birthday: :tada:
    
    Amém :pray:
    
Saída:

Feliz Aniversário! :birthday: :tada:

Amém :pray:


**Observação**

Sites com códigos: <https://gist.github.com/rxaviers/7360908> ; <https://www.webfx.com/tools/emoji-cheat-sheet/> ; [Emojiterra](https://emojiterra.com/pt/) ; 

***

### 4.Realçar

Alguns processadores Markdown permitem destacar o texto, basta colocá-lo entre dois símbolos de igual (==). Por exemplo:

    A Física possui duas grandezas muito importantes: o ==tempo== e a ==distância==.
    
Saída:

A Física possui duas grandezas muito importantes: o ==tempo== e a ==distância==.


### 5. Notas de Rodapé

Para criar uma nota de rodapé basta colocar um circunflexo e em seguida identificador (pode ser um número ou letra), ambos entre colchetes, desta forma: [^1]. Depois, adicionamos dois pontos (:) e o conteúdo da nota de rodapé. Veja o exemplo (tirado do site <https://www.markdown.net.br/sintaxe-estendida/>):

    Aqui está uma nota de rodapé simples[^1]. Aqui está uma nota de rodapé mais elaborada[^bignote].

    [^1]: Esta é a primeira nota de rodapé.

    [^bignote]: Aqui está uma com vários parágrafos e código.

        Recuar parágrafos para incluí-los na nota de rodapé.

        `{ meu código }`

     Adicione quantos parágrafos desejar.

Temos a seguinte saída:

Aqui está uma nota de rodapé simples[^1]. Aqui está uma nota de rodapé mais elaborada[^bignote].

[^1]: Esta é a primeira nota de rodapé.

[^bignote]: Aqui está uma com vários parágrafos e código.

    Recuar parágrafos para incluí-los na nota de rodapé.

    `{ meu código }`

    Adicione quantos parágrafos desejar.


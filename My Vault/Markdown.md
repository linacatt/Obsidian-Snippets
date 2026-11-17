---
date: 2026-11-14
type: Note
tags:
---
---
O Obsidian funciona com **Markdown**, então é importante lembrar quais são os comandos. Algumas referências:

- [Sintaxe Básica do Obsidian](https://help.obsidian.md/syntax) 
- [Markdown do Obsidian](https://help.obsidian.md/obsidian-flavored-markdown)
- [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)

___ 

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

___

**Negrito** ** ** ou __ __ **Ctrl + B**

*Itálico* * * ou _ _ **Ctrl + I**

~~cortado~~ ~~ ~~ **Ctrl + S

==Marcador== == == 

***Negrito itálico*** *** *** ou ___ ___ 

Exceção \ \ \**This line will be italic and show the asterisks*\*
___

**Links internos:** 
- Wikilink: `[[Three laws of motion]]`
- Markdown: `[Three laws of motion]`

**Links externos:**
- [Obsidian Help](https://help.obsidian.md) :  `[Obsidian Help](https://help.obsidian.md)`
- Imagem da web:  `![Raposa](https://tudoraposa.com.br/wp-content/uploads/2024/06/Raposa-do-Campo-1.webp)`

Exemplo de imagem da web:
 ![Raposa|250](https://tudoraposa.com.br/wp-content/uploads/2024/06/Raposa-do-Campo-1.webp) 

___

**Quotes**

> A Raposa do Campo (*Lycalopex vetulus*), também conhecida como raposinha-do-cerrado, é uma espécie fascinante e pouco conhecida do vasto bioma brasileiro.


> [!Nota:] 
> Basta escrever `[!Nota]`para criar uma caixa como essa!
> 


> [!note]-  Note
> Contents

> [!abstract]-  Abstract
> Contents

> [!info]-  Info
> Contents

> [!todo]-  Todo
> Contents

> [!tip]-  Tip
> Contents

> [!success]-  Success
> Contents

> [!question]-  Question
> Contents

> [!warning]-  Warning
> Contents

> [!failure]-  Failure
> Contents

> [!danger]-  Danger
> Contents

> [!bug]-  Bug
> Contents

> [!example]-  Example
> Contents

> [!quote]-  Quote
> Contents

___

- Ponto 1
- Ponto 2
- Ponto 3

1. Numeral 1
2. Numeral 2
3. Numeral 3

4) Numeral 4
5) Numeral 5
6) Numeral 6

**Ctrl + L**
- [x] Tarefa 1
- [x] Tarefa 2
- [-] Tarefa 3 
	- [-] Sub-tarefa 1
	- [-] Sub-tarefa 2

___

**Régua Horizontal**: *** ou --- ou ___

***

**Código:**
Escrever dentro de `tracinhos` faz com que o texto fique em formato de código 

~~~~
Colocar ``` ou ~~~ ao redor do texto criam um bloco de código.
~~~~

---

**Nota de rodapé:**
Para colocar notas de rodapé, basta usar [^1] no texto. Ativa no modo de leitura.

[^1]: Isso é uma nota de rodapé

---

**Comentários:**
São visíveis apenas no modo de edição. Basta usar dois % ao redor do texto. %% Desse jeito, por exemplo.%%

---

**Escape syntax:**
Símbolos usados para bloquear o markdown. São eles: 
- Asterisk: `\*`
- Underscore: `\_`
- Hashtag: `\#`
- Backtick: `` \` ``
- Pipe (used in tables): `\|`
- Tilde: `\~`

--- 

**Tabelas:**
Para fazer tabelas, você usa `|` e `:---:` para criar uma tabela. O dois pontos definem a centralização. 

| Tabela |  A  |  B  |  C  |
| :----: | :-: | :-: | :-: |
|   1    |     |     |     |
|   2    |     |     |     |
|   3    |     |     |     |

---

- [ ] `space` Unchecked
- [x]  `x` Checked
- [>]  `>` Rescheduled
- [<]  `<` Scheduled
- [!]  `!` Important
- [-]  `-` Cancelled
- [/]  `/` In Progress
- [?]  `?` Question
- [*]  `*` Star
- [n]  `n` Note
- [l]  `l` Location
- [i]  `i` Information
- [I]  `I` Idea
- [S]  `S` Amount
- [p]  `p` Pro
- [c]  `c` Con
- [b]  `b` Bookmark
- ["]  `"` ~~Quote~~

---

- [0]  `0` Speech bubble 0

- [1]  `1` Speech bubble 1

- [2]  `2` Speech bubble 2

- [3]  `3` Speech bubble 3

- [4]  `4` Speech bubble 4

- [5]  `5` Speech bubble 5

- [6]  `6` Speech bubble 6

- [7]  `7` Speech bubble 7

- [8]  `8` Speech bubble 8

- [9]  `9` Speech bubble 9

---
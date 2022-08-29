---
marp: true
theme:  gaia
paginate: false
---

<!-- class: invert --> 
# <!--fit--> Terminal
<!-- footer: Grupo 1 | T02 - CTD | Introdução à Informática | Digital House | 2022-->

Grupo 1:
Isaias Moresco 
Lênio Celso Brandão Guerreiro Barbosa 
Stefany Jenifer Chagas dos Santos
Viviane Akemi Okuma
Zilmar Pires Martins Junior

<style scoped>
{font-size: 26px} 
footer {font-size: 16px; text-align:center}
</style>

![bg right](https://i.ebayimg.com/images/g/xUsAAOSwVO1f2vKp/s-l400.jpg)
![bg](https://www.codingdojo.com/blog/wp-content/uploads/codelaptop.jpg)

---

## Uma Breve História do Terminal
Viviane Akemi Okuma

<style scoped>
footer {font-size: 20px; text-align:center}
</style>

![bg left:40%](https://c.tenor.com/t4XpGIkuCK8AAAAC/senta-que.gif)

---

#### Teletipo modelo com leitor de fita perfurada (1976)
##### Terminal de computador emulado (1978)

<style scoped> 
h4{font-size:25px; text-align:left} 
h5{font-size:25px; text-align:right}
</style>
<style>footer{text-align:center}</style>

![bg 50%](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR0RNSOrZvHseVZL3-4VIJ3VJzz50lwk75LAiR3GzdBedgaqwoZDStyFjjINSjaVd7MMGs&usqp=CAU)
![bg 70%](https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/DEC_VT100_terminal.jpg/800px-DEC_VT100_terminal.jpg)

---

Prompt de Comando do Windows

<style scoped>{text-align:center}</style>

![bg 70%](https://uploaddeimagens.com.br/images/004/001/020/full/Sem_t%C3%ADtulo.png?1661780083)

---

Através da CLI podemos dar instruções ao sistema do computador.

Instruções básicas como:
•	criar uma pasta (mkdir);
•	criar umarquivo (touch);
•	mover um arquivo (mv);
•	mostrar a árvore de diretórios (tree).

Para abrir um terminal:
•	no Windows podemos usar a barra de pesquisa e digitar cmd ou powershell;
•	no Mac pressionar as teclas command + space e digitar terminal;
•	no Linux pressionar as teclas CTRL + Alt + T ou digitar terminal na barra de pesquisa.

<style scoped>{font-size:30px}</style>

---

## Características da Interface de Linhas de Comando (CLI)
Stefany Jenifer Chagas dos Santos

<style scoped>
footer {font-size: 20px; text-align:center}
</style>

![bg right:40%](https://developer.okta.com/assets-jekyll/blog/why-clis-suck/cli-laptop-social-b259289b3e4846abdd294e4fa87370e1838e0503d000e986a0f4e4125d79f05b.jpg)

---

# Shell
Lênio Celso Brandão Guerreiro Barbosa

<style scoped>
footer {font-size: 20px; text-align:center}
</style>

![bg left:40%](https://www.codigofonte.com.br/wp-content/uploads/2014/08/shell.jpg)

---

1. O que é Shell e como ele funciona?
2. Modo interativo e não interativo do Shell
3. Entradas e Saídas:
3.1 stdin (standard input)
3.2 stdout (standard output)
3.3 stderr (standard error)
4. Vantagens do Shell

---


<!-- _backgroundColor: white -->


<style scoped> footer{color:black}</style>

![bg 80%](https://i.ibb.co/4m4QBMP/processo.png)
![bg 80%](https://i.ibb.co/c1LJLv6/desv-terminal.png)

---

## Tipos de CLI
Zilmar Pires Martins Junior

<style scoped>
footer {font-size: 20px; text-align:center}
</style>

![bg right:40%](https://external-preview.redd.it/JE7zUGqfQAurmOdzn3w3oZD4oALNUhpKKie0Pv9L4HE.jpg?width=640&crop=smart&auto=webp&s=cde2d17780870ea1d4ce110759c1141e424aa444)

---

1. Shell
É no shell que a “mágica” acontece, ou seja, é nele que os programas, scripts e comandos são executados.
2. Bash
Idealizado por Steven Bourne, em 1977
Bash é o acrônimo de Bourne Again Shell
É o padrão na maioria das distribuições Linux
3. Windows Shell
Interface gráfica do usuário para o sistema operacional Microsoft Windows. 
4. Power Shell
Solução de automação de tarefas multiplataforma

<style scoped>{font-size:30px}</style>

---

## Considerações Finais
Isaias Moresco

<style scoped>
footer {font-size: 20px; text-align:center}
</style>

![bg left:40%](https://4.bp.blogspot.com/-AICVY4YVDyI/WELMk5iMj0I/AAAAAAAAM98/ajCWxyuL5eUOzL4hhFwvZkZi3Loy9dEEQCLcB/s640/IMAGEM%2B1600%2B-%2BCHECKLIST%2B-%2BO%2BBLOG%2BDO%2BMESTRE.jpg)

---
As ferramentas que usam CLI trazem uma maior produtividade para programadores e administradores de sistemas.

- São de simples aprendizado e funcionamento.
- Se o usuário lembrar de apenas parte de um comando, basta dar TAB na maioria dos casos, para autocompletar
- Podem armazenar um histórico de comandos que podem ser editados, para serem executados futuramente
- Permitem criar e rodar scripts para automação de tarefas repetitivas que seriam muito complexas em uma GUI

<style scoped>{font-size:30px}</style>

---
Exemplo: Baixar um programa como o Git para Windows.

Na GUI teríamos que: 
1. Acessar o site do desenvolvedor 
2. Clicar no botão de download 
3. Acessar o menu de downloads do navegador 
4. Dar 2 cliques para iniciar a instalação 
5. Clicar em “Sim” para autorizar a instalação 
6. Seguir o passo-a-passo da instalação clicando várias vezes em “Next” 
7. Instalação concluída ## Com 

Com uma CLI: 
1. Executar o Windows terminal como admin. 
2. Inserir o comando: `winget install git.git`

<style scoped>{font-size:25px}</style>

---

![bg 80%](https://isaiasmoresco.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F4d2b9d79-bafe-49b7-a93c-b951de8dfa98%2FUntitled.png?table=block&id=3916c755-c47c-4c14-baaa-3a72abe5ed1d&spaceId=f139d8e0-266c-4f8b-b970-75074b1016a6&width=2000&userId=&cache=v2)

---

## Fontes bibliográficas:

https://pt.wikipedia.org/wiki/Terminal_(inform%C3%A1tica)

https://www.hostinger.com.br/tutoriais/o-que-e-cli#As_Origens_do_CLI

https://dev.to/womakerscode/o-que-e-o-terminal-1bgp

https://blog.betrybe.com/tecnologia/tudo-sobre-cli/

https://segredo.dev/o-que-e-shell/

http://wiki.inf.ufpr.br/maziero/doku.php?id=unix:shell_avancado#:~:text=Entradas%20e%20sa%C3%ADdas%20padr%C3%A3o,-A%20maioria%20dos&text=Entrada%20padr%C3%A3o%20(%20stdin%20%2D%20standard%20input,%C3%A9%20referenciado%20pelo%20descritor%201.

<style scoped>{font-size:25px} h2{font-size:50px}</style>

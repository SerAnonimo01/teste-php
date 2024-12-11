# Primeiro Site com PHP 💻

<p align="center">
  <img align="center" src="https://wallpapers-clan.com/wp-content/uploads/2024/08/man-dark-city-in-the-rain-gif-desktop-wallpaper-preview.gif" alt="Imagem">
</p>


> *OBS: Este é um repositório desenvolvido durante o desafio do curso de Geração Tech Unimed-BH | Fullstack da [DIO](https://www.dio.me/)* 

## Sumário
- Resumo ✍🏻
- Linguagem e Servidor 💻
- Explicação dos Códigos 🚀
- Conclusão 🐜

## Resumo ✍🏻
Esse projeto-teste é uma primeira vista do que seria utilizar em um site PHP, tem o objetivo principal de apresentar a linguagem de programação.

## Linguagem e Servidor💻

A linguagem utilizada nesse projeto-teste foi o PHP:

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="42" alt="php logo"  />
</div>

E estamos utilizando o *Apache*, (Servidor HTTP Apache), é um servidor de código aberto no qual possibilita que donos de sites mostrem e mantenham seus conteúdos na internet:

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original.svg" height="42" alt="apache logo"  />
</div>

## Explicação dos Códigos 🚀
```
<html>
    <head>
        <title>Teste site em PHP</title>
    </head>
    
    <body>

        <?php
            for ( $i = 0 ; $i < 10 ; $i++) {
                print( "Linha número " . $i . "<br />");
            }
        ?>

        </body>

</html>
```
---

- `<html>` e `</html>`

Elas ditam o início e o fim do documento HTML, todo o conteúdo da página web (site) estará dentro dessas tags.

---

- `<head>` e `</head>`

Essa parte contém informações sobre a página que não são diretamente visíveis no corpo do site. Inclusive, após ele, colocaremos o título.

---

- `<title>Teste site em PHP</title>`

Define o título da página que será exibido na aba do navegador. Nesse caso, será "Teste site em PHP".

---
- `<body>` e `</body>`

Tudo entre essas tags será o conteúdo principal exibido no navegador.

---

- `<?php` e `?>`

Delimitam o bloco de código PHP. Tudo dentro dessas tags será interpretado e executado pelo servidor.

---

- `for ( $i = 0 ; $i < 10 ; $i++)`

Um laço de repetição for que executa o código dentro das chaves {} enquanto a condição é verdadeira. 

`$i = 0`: Inicializa a variável $i com o valor 0;

`$i < 10`: O código dentro do laço será executado enquanto $i for menor que 10;

`$i++`: Incrementa o valor de $i em 1 a cada iteração.

---

- `print( "Linha número " . $i . "<br />")`

o `print` vai exibir o texto no navegador para cada iteração;

`"Linha número "`: Texto base;

`. $i`: Concatena o valor atual da variável `$i` ao texto;

`"<br />"`: Adiciona uma quebra de linha HTML após cada texto exibido.

---
E para acessar esse servidor nós colocamos no navegador *localhost/nome-do-arquivo.php*

## Conclusão 🐜

Esse projeto-teste proporcionou um aprendizado introdutório sobre o uso de PHP para desenvolvimento web e sua interação com o servidor Apache. Através de exemplos simples, foi possível explorar conceitos fundamentais, como estrutura básica de um documento HTML e integração do PHP em sites, conceitos são essenciais para a criação de sites dinâmicos.

Na aula prática também foram mostrados outros modos de criar essa primeira vista do *PHP* e o *Apache*, porém preferi por armazenar esse primeiro conhecimento e observar minha evolução ao decorrer do curso; uma base sólida para explorar projetos mais avançados no futuro.

---
//Feito por Luke 🐉//

# Síntaxe do HTML
---
### O que fazer?

##### 1. Reescreva a linha a seguir utilizando identação e de forma que as tags abram e fechem na ordem adequada:

                <div>
                <p>Esse é um parágrafo que antecede uma lista:</p>
                <strong>não ordenada:</strong>
                    <ul>
                        <li>Item de lista 01</li>
                        <li>Item de lista 02</li>
                        <li>Item de lista 03</li>
                        <li>Item de lista 04</li>
                    </ul>
                </div>

##### 2. Marque as tags container:
[ ] `<img>` 
[ ] `<strong>`  
[ ] `<br>` 
[ ] `<body>`
[ ] `<input>`
[ ] `<hr>`

#####  3. Indique a tag HTML correspondente para cada um dos elementos a seguir e o máximo de atributos que você souber ou lembrar para cada, conforme modelo:
**Exemplo:** Parágrafo: `<p ~~align=""~~> </p>` - *o atributo align não é mais válido na versão corrente do html (HTML5)*
- Imagem: 
- Formulário:
- Quebra de linha:
- Link:
- Campo de formulário tipo texto:
- Campo de formulário tipo checkbox:
- Ênfase (negrito): 
- Ênfase (itálico): 
- Botão:
- Linha horizontal:
- Título da página:
- Tabela
- Linha de Tabela
- Coluna de Tabela  

__
### Solução
##### 1. Reescreva a linha a seguir utilizando identação e de forma que as tags abram e fechem na ordem adequada:
```
<div>
    <p>Esse é um parágrafo que antecede uma lista:<strong>não ordenada:</strong></p>
    <ul>
        <li>Item de lista 01</li>
        <li>Item de lista 02</li>
        <li>Item de lista 03</li>
        <li>Item de lista 04</li>
    </ul>
</div>
```
##### 2. Marque as tags container:
[ ] `<img>`
[x] `<strong>`  
[ ] `<br>` 
[x] `<body>`
[ ] `<input>`
[ ] `<hr>`
#####  3. Indique a tag HTML correspondente para cada um dos elementos a seguir e o máximo de atributos que você souber ou lembrar para cada, conforme modelo:
> *Solução com os atributos válidos mais comuns, consulte http://www.w3schools.com/ para uma referência completa:*
- Imagem: `<img src="" alt="" width="" height="" id="" class="">`
- Formulário: `<form action="" name="" method="" id="" class=""></form>`
- Quebra de linha: `<br>`
- Link: `<a href="" name="" target="" rel="" id="" class=""></a>`
- Campo de formulário tipo texto: `<input type="text" name="" size="" max="" min="" disabled required id="" class="">`
- Campo de formulário tipo checkbox: `<input type="checkbox" name="" value=""  disabled checked id="" class="">`
- Ênfase (negrito): `<strong id="" class=""></strong>`
- Ênfase (itálico): `<em id="" class=""></em>`
- Botão: `<button name="" value="" form="" disabled id="" class=""></button>`
- Linha horizontal: `<hr id="" class="">`
- Título da página: `<title></title>`
- Tabela: `<table id="" class=""></table>`
- Linha de Tabela: `<tr id="" class=""></tr>`
- Coluna de Tabela: `<td id="" class=""></td>`
___
***Data:** 11/07/2016*  
***Autor:** http://www.fabioaleixo.com.br/, para http://www.voltdata.info/*

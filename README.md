# MaskInputJS
 Biblioteca CDN  máscaras de input no Html, utilizando JavaScript

<div style='display:flex;'>
  <img src='https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black'/>
   &nbsp;
  <img src='https://img.shields.io/badge/jsDelivr-E84D3D.svg?style=for-the-badge&logo=jsDelivr&logoColor=white'/>
 </div>


## Instalação:
---
- Inclua a tag de script abaixo em seu documento:.

```html
<script src='https://cdn.jsdelivr.net/gh/miguelhp373/MaskInputJS/maskjs@1.2/maskjs.min.js'></script>

```

<br/>

## Exemplo de Utilização:
---

Adicione a classe de sua <a href='https://github.com/miguelhp373/MaskInputJS#masc%C3%A1ras'>máscara</a> desejada no seu  `<input type='text' class='maskclass'>`


```html
    <body>
        <input type='text' class='inputnumberphone'>
    </body>

```

<br/>

## Mascáras
---
- Telefone :
&nbsp;
    `(11)91111-1111`
    <br/>
    ```html
    <input type='text' class = 'inputnumberphoneformat'/>
    ``` 

- CPF :
&nbsp;
    `111.111.111-11`
    <br/>
    ```html
    <input type='text' class = 'inputCpfformat'/>
    ``` 

- Data (DD/MM/AAAA) :
&nbsp;
    `00/00/0000`
    <br/> 
     ```html
    <input type='text' class = 'inputdateformat_ddmmaaaa'/>
    ``` 
     

- Data Hora (DD/MM/AAAA 00:00) :
&nbsp;
    `00/00/0000 00:00`
    <br/>
    ```html
    <input type='text' class = 'inputdateformat_ddmmaaaahhmm'/>
    ```



## License

[Apache License 2.0](COPYING)

Feito com 💜 &nbsp;por Miguel Henrique 👋




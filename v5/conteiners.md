# Bootstrap 5 - Conteiners

##  Tipos:
   
- ``` .container ``` - ocupa uma largura fixa e responsiva
- ``` .container-fluid ``` - ocupa a largura total da tela sempre

~~~html
<div class="container">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in malesuada erat, vitae aliquet nisi. 
        Donec iaculis ante vitae ante.</p>
</div>

<div class="container-fluid">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in malesuada erat, vitae aliquet nisi. 
        Donec iaculis ante vitae ante.</p>
</div>
~~~

## Adicionando um padding vertical

- ```pt-5```: padding superior (1 a 5)

~~~html
<div class="container pt-5"></div>
~~~

## Adicionando uma margem vertical

- Margem acima e abaixo do conteiner.

~~~html
<div class="container my-5"></div>
~~~

## Adicionando bordas

~~~html
<div class="container border"></div>
~~~

## Adicionando cores

- Para o background:
    - bg-dark 
    - bg-primary
- Para o texto:
    - text-white

~~~html
<div class="container bg-dark text-white"></div>
~~~

## Conteiners responsivos

- Modifica o max-width do conteiner em diferentes tamanhos de tela.
- Exemplo:
   - container-sm - em telas menores que 576px ocupa 100% da largura da tela.
   - container-xxl - em telas menores que 1320px ocupa 100% da largura da tela.

~~~html
<div class="container-sm border">.container-sm</div>
<div class="container-md mt-3 border">.container-md</div>
<div class="container-lg mt-3 border">.container-lg</div>
<div class="container-xl mt-3 border">.container-xl</div>
<div class="container-xxl mt-3 border">.container-xxl</div>
~~~




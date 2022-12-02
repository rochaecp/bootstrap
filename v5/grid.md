# Bootstrap - Grid

- Feito com flexbox.
- Permite até 12 colunas na página (não é necessário utilizar todas).

## Classes de grid

| Classe | Dimensão da tela |
| --- | ---|
| ```.col-```       | tela < 576px |
| ```.col-sm-```    | tela >= 576px |
| ```.col-md-```    | tela >= 768px |
| ```.col-lg-```    | tela >= 992px |
| ```.col-xl-```    | tela >= 1200px |
| ```.col-xxl-```   | tela >= 1400px |

- Obs.: Se você quiser especificar a mesma largura para ```sm``` e ```md``` basta especificar a largura de ```sm```.

## Criando 3 colunas de tamanho igual

Faz com que o Bootstrap torne as larguras iguais automaticamente.  

~~~html
<div class="row">
    <div class="col border">Coluna 1</div>
    <div class="col border">Coluna 2</div>
    <div class="col border">Coluna 3</div>
</div>
~~~

## Criando 3 colunas responsivas

Cria 3 colunas com a mesma largura do tamanho 576 para cima.  
Para tamanhos menores que 576 cria uma coluna apenas.  

~~~html
<div class="row">
    <div class="col-sm-4 border">Coluna 1</div>
    <div class="col-sm-4 border">Coluna 2</div>
    <div class="col-sm-4 border">Coluna 3</div>
</div>
~~~
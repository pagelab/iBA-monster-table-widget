Monster Table Widget
=====================

![monstertable](https://f.cloud.github.com/assets/1451087/1291235/fd7ef422-303e-11e3-9ea7-d07d03e64103.png)


Um widget para apresentação de tabelas gigantescas no [iBooks Author](http://www.apple.com/ibooks-author/)

*A widget for presentation of huge tables in iBooks Author*

##O problema
Tabelas muito extensas são um desafio para eBooks produzidos com o programa iBooks Author, da Apple. 

Há uma limitação evidente na apresentação de tabelas com um número muito elevado de colunas ou linhas. 

O recurso padrão do programa não é uma boa opção nesses casos, e tende a deixar tabelas muito extensas com texto ilegível. 

##A solução

Este widget oferece uma solução para esse problema, embutindo a tabela em um widget HTML com plugins JQuery para controlar a visualização de acordo com a área disponível para apresentá-la.

## Recursos

* Scrolling vertical e horizontal do conteúdo
* 

##Como funciona
* Substitua o código de tabela que está no arquivo `tabela.html` pela sua tabela em HTML para ter automaticamente o *scrolling* vertical e horizontal. Provavelmente seja necessário também alterar a largura da tabela no arquivo CSS padrão (`css/style.css`) para torná-la visualmente mais agradável. 
* Se desejar ter uma navegação de página e outros *goodies* do plugin *footable*, altera a largura da tabela para XXX pixels e ajuste os data-attributes de acordo com o tutorial do *Footable*
* Adicione a extensão `.wdgt` à pasta raiz do widget para que o Mac OS automaticamente a reconheça como um widget (veja que o ícone da pasta será alterado mudará).

##Pré-visualização do widget
Ao inserir 

## Agradecimentos

Esta solução se baseia no código de vários excelentes projetos pela web. Agradecimentos a:

* [Scrolling iBooks HTML Widget Boilerplate] (https://github.com/edwilde/iBooks-HTML-Widget-Boilerplate)
* [jQuery custom content scroller](http://manos.malihu.gr/jquery-custom-content-scroller/)
* 


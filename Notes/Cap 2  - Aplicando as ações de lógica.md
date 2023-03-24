
## Imersão do conhecimento no Front-End

	No visual Studio Code, existem as extensões que basicamente são ferramentas que ajudam a melhorar aparência e ajudar no desenvolvimento do seu programa. Muito útil porém, devemos tomar cuidado para não instalar muitas extensões, para não deixar o VS Code lento.


## Tags são caixas

As tags presentes dentro de um HTML funcionam como caixas, e com elas nós organizamos  novos projetos. A melhor maneira de organizar, é dividir os arquivos com seus naturais. Por exemplo: Criarmos uma pasta apenas para imagens, uma pasta para o CSS, e uma pasta para JS. Fora está organização, precisamos do nosso arquivo *Index.html* que é o arquivo principal de um projeto.

Estrutura básica de uma tag:

	<nome da tag>"Conteúdo presente na tag" </nome>

Exemplo:

	<div> Bom dia! </div>

Podemos utilizar o ponto de exclamação, para conseugir criar uma estrutura básica de um HTML, que acompanha: head, doctype html, os metas, o html lang e o body.

	<!DOCTYPE html>
	
	<html lang="en"> // a lingua que o navegador irá ler
	
	<head>
	
	    <meta charset="UTF-8"> // pacote de caracteres que estarão presentes no projeto
	
	    <meta http-equiv="X-UA-Compatible" content="IE=edge">
	
	    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	
	    <title>Document</title> // titulo que fica na aba do navegador

	</head>
	<body>
	// Aqui fica todo o conteúdo da página
	</body>
	</html>

### Conceitos de caixas

Podemos comprar as tagas como caixas, e caso colocarmos um tag dentro da outra, irá funcionar como caixas dentro de caixas, que se organizarão de acordo com a ordem que iniciam. Desta forma é possível organizar o código de uma maneiro muito mais fácil e simples. Por padrão as tagas se comportam de 2 formas:]

Tags BLOCK, ocupam todo o espaço da linha que estão, dessa forma não é possivel mostrar nada do seu lado. Como por exemplo: 

	<p></p> <h1></h1> <li></li>

Tags INLINE, ocupam apenas o tamanho do seu contéudo, perimitndo que outras caixas sejam exibidas ao seu lado.

	<a></a> <img>


#### Tag Div

É muito utilizada como um container, nela colocamos os conteúdos de maneiro divida, feita para poder guardar qualquer tipo de conteúdo. Porém a mágica irá acontecer apenas no CSS, para a estilização das divs.


#### CSS

É onde é feita a estilização do projeto. Fica separado em um arquivo .css. A estilização é a estilização das tags presente no projeto, dessa forma podemos mudar as propriedades de qualquer tag no projeto, desde tamanho até mesmo formato e e como ela irá se comportar na página.
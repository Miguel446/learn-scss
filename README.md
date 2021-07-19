# learn-scss
Project to learn the basics of SCSS

// Anotações sobre o uso de SCSS //

Obs: É necessário compilar o arquivo .scss para css para ser possível adicionar esses estilos no html

1 - Variáveis
	$primaryBtn: rgb(49, 201, 44);
	$variavel: valor;
	- aceita parametros de css como cor, alinhamento
    - tbm aceita valores numéricos e strings

2 - Nesting
    facilita a organização de estilos dentro de uma tag específica, podendo ser necessário utilizar o caracter '&' em determinados componentes
    e para utilizar eventos como o 'hover'

3 - Mixins
    são como funções javascript, onde podem ser adicionados parametros css e que permitem a reutilização desses parametros em qualquer parte do codigo

4 - Imports
    possibilita a separação de estilos em arquivos diferentes, podendo criar um arquivo apenas para mixins ou outro apenas para variáveis e ao trabalhar
    com um framework como Angular por exemplo, pode-se salvar os estilos de cada componente em um arquivo.scss diferente

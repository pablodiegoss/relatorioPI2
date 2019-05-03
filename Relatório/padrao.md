# Padrões para escrita do texto

```
Cada uma das áreas possuirá uma pasta específica para escrita do texto, que armazenará todos arquivos pertinentes (imagens, .tex, etc). O gerente de cada área poderá modificar apenas sua pasta. Haverá ainda uma pasta chamada "geral", que contém o texto de introdução e conclusão   
```

## Imagens
```
Dentro da pasta de cada área haverá uma pasta "figuras", onde serão salvas as figuras seguindo o seguinte formato de nome:
	- cod_pcX_YY_descrição.png
Onde "cod" corresponde ao código da pasta (as três primeiras letras do nome):
	- comunicação: com
	- energia:     ene
	- esrutura:    est
	- geral:       ger
	- sensores:    sen
	- software     sof
"X" corresponde ao ponto de controle atual
"YY" ao número da imagem, seguindo sequencialmente a medida que são colocadas ao texto (não reflete necessariamente a ordem em que elas aparecerão no relatório)
O formato ".png" não é obrigatório
A descrição da imagem é opcional
Os labels utilizados para referência devem ser o mesmo nome do arquivo da imagem sem descrição e sem a extensão. Ex: "cod_pcX_YY"
```

## Tabelas
```
Preferencialmente devem ser geradas nativamente no latex
Devem seguir o seguinte padrão para label:
	- tab_cod_pcX_YY
```

##Referências Bibliográficas

```
Podem ser geradas no site https://truben.no/latex/bibtex/
A "key" deve seguir o seguinte padrão:
	- bib_cod_YY_autor
```


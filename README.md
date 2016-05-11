# cols.fab

## Usage

### Explicit (.cols-3)
3 columns
```html
	<div class="cols cols-3">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
	</div>
```
### Dynamic (.colsd)
Nombre de columns flexible 
example: 
	- Si .cols contient 3 .col les columns vont prendre 33% de width; 
	- Si .cols contient 4 .col les columns vont prendre 25% de width;
```html
	<div class="cols colsd">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
	</div>
```
### Explicit avec margins (.cols-4, .colsm)
4 columns avec marge
```html
	<div class="cols cols-4 colsm">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
		<div class="col">4</div>
	</div>
```
### Dynamic avec margins (.colsd, colsm)
Dynamic avec marge
```html
	<div class="cols colsd colsm">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
		<div class="col">4</div>
		<div class="col">5</div>
	</div>
```
### Sur plusieurs rows (.cols-3)
Fonctionne seulement Explicit
```html
	<div class="cols cols-3 colsm">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
		<div class="col">4</div>
		<div class="col">5</div>
		<div class="col">6</div>
	</div>
```
### Columns avec différents widths (.col.w33, .col.w66)
Fonctionne seulement Explicit
```html
	<div class="cols cols-2">
		<div class="col w33">1</div>
		<div class="col w66">2</div>
	</div>
```

## Variables
Les variables par défaut peuvent être changées au besoin

### Margin 
$m: 3%;

### Nombre maximal de columns
$colnb: 8;

### Liste des widths custom
$widths: w20 20%, w25 25%, w30 30%, w33 33.33%, w40 40%, w50 50%, w60 60%, w66 66.66%, w75 75%, w80 80%;
	

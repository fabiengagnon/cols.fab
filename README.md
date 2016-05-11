# cols.fab

## Usage

### Explicit (.cols-3)
	3 columns
<pre>
	<div class="cols cols-3">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
	</div>
</pre>
### Dynamic (.colsd)
	Nombre de columns flexible 
	example: 
		- Si .cols contient 3 .col les columns vont prendre 33% de width; 
		- Si .cols contient 4 .col les columns vont prendre 25% de width;
<pre>
	<div class="cols colsd">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
	</div>
</pre>
### Explicit avec margins (.cols-4, .colsm)
  4 columns avec marge
<pre>
	<div class="cols cols-4 colsm">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
		<div class="col">4</div>
	</div>
</pre>
### Dynamic avec margins (.colsd, colsm)
  Dynamic avec marge
<pre>
	<div class="cols colsd colsm">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
		<div class="col">4</div>
		<div class="col">5</div>
	</div>
</pre>
### Sur plusieurs rows (.cols-3)
  Fonctionne seulement Explicit
<pre>	
	<div class="cols cols-3 colsm">
		<div class="col">1</div>
		<div class="col">2</div>
		<div class="col">3</div>
		<div class="col">4</div>
		<div class="col">5</div>
		<div class="col">6</div>
	</div>
</pre>
### Columns avec différents widths (.col.w33, .col.w66)
  Fonctionne seulement Explicit
<pre>
	<div class="cols cols-2">
		<div class="col w33">1</div>
		<div class="col w66">2</div>
	</div>
</pre>
	

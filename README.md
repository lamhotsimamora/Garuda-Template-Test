# Garuda-Template-Test

### Demo
<a href="https://lamhotsimamora.github.io/Garuda-Template-Test/">Demo</a>

### HTML
```
<div class="container" id="app">
	
</div>

<template id="template_buah">
	<br>
	<h2>Nama-nama buah :</h2>
	<p class="info">
		<ul class="list-group">
		  <li class="list-group-item active">Apel</li>
		  <li class="list-group-item">Jeruk</li>
		  <li class="list-group-item">Jambu</li>
		  <li class="list-group-item">Marqisa</li>
		  <li class="list-group-item">Mangga</li>
		  <li class="list-group-item">Rambutan</li>
		  <li class="list-group-item">Sirsak</li>
		  <li class="list-group-item">Pisang</li>
		</ul>
	</p>
	<button class="btn btn-primary btn-md" onclick="test();">Info Property & Method</button>
	 <hr>
</template>
```

### Syntax Javascript
```
	$app = __({
		el:'app'
	});
	$buah = new GarudaTemplate({
		id:'template_buah'
	}).to($app);
```
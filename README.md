# Aprender Vue

## Expresiones y Propiedades
Una expresión representa el valor de las propiedades de data,se puede usar código js, sumar números, expresiones boolenas, funciones.

``` html
<h1>{{ title }}</h1>
<p>{{ 1 + 1 + 1 }}</p>
<p>{{ true || false }}</p>
<p>{{ true ? true : false }}</p>
<p>{{ 'string'.toUpperCase() }}</p>
<p>{{ JSON.stringify({ name: 'nacho'}) }}</p>
```

Si deseo inspeccionar en consola usar:

``` js
app.title
```
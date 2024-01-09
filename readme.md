
1. Que son los frameworks

Campo de trabajo que nos orienta en el uso de herramientas que ofrece y ser más eficientes/optimizar el trabajo, dado que este es repetitivo. Permite que el desarrollo sea más rápido.

2. Que es boostrap CSS

El framework más usado es Bootstrap

3. Que maneras de agregar a nuestro proyecto tenemos

Para fines educativos importamos el framework por url ([Download · Bootstrap v5.3 (getbootstrap.com)](https://getbootstrap.com/docs/5.3/getting-started/download/)), sin embargo, en producción lo correcto es trabajarlo descargando el archivo ([Get started with Bootstrap · Bootstrap v5.3 (getbootstrap.com)](https://getbootstrap.com/docs/5.3/getting-started/introduction/))


4. Que son los break points de boostrap y explicar

Son los limites a partir de los cuales varia las dimensiones de los elementos de la pagina, en bootstrap van de Extra small (<576) a Extra extra large (xxl >=1440)

5. Que son los container de boostrap y explicar

Clase que limita que tan grande es el espacio en el que trabajamos toda la pagina, incolucra los atributos: margin 0 auto; padding left rigth y width.

6. Que son las grillas de boostrap y explicar como son cuantos son

Forma de cuadricular la pagina
Siempre son 12 columnas
Se pueden elegir numeros de columnas colocando col-#
Si no suma las columnas que he puesto, la columna no especificada se maneja

7. Que son los utilities de boostrap y como usarlos

Son clases que se pueden aplicar para especificar configuración de una clase mayor, se utilizan agregandolo como clase al elemento
[Flex · Bootstrap v5.3 (getbootstrap.com)](https://getbootstrap.com/docs/5.3/utilities/flex/#justify-content)

d-flex-> display:flex
justify-content-center-> justify-content:center;


8. Que son los componentes de boostrap y dar ejemplo de 3 no vistos en clase

Son un elemento o grupo de estos que ya estan codeados, usamos en clase acordion y carousel. Aparte podemos ver:

Buttons: <button type="button" class="btn">Base class</button>

Listas:

<ul class="list-group">
  <li class="list-group-item">An item</li>
  <li class="list-group-item">A second item</li>
  <li class="list-group-item">A third item</li>
  <li class="list-group-item">A fourth item</li>
  <li class="list-group-item">And a fifth one</li>
</ul>

Progress:

<div class="progress" role="progressbar" aria-label="Basic example" aria-valuenow="0" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar" style="width: 0%"></div>
</div>
<div class="progress" role="progressbar" aria-label="Basic example" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar" style="width: 25%"></div>
</div>
<div class="progress" role="progressbar" aria-label="Basic example" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar" style="width: 50%"></div>
</div>
<div class="progress" role="progressbar" aria-label="Basic example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar" style="width: 75%"></div>
</div>
<div class="progress" role="progressbar" aria-label="Basic example" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar" style="width: 100%"></div>
</div>


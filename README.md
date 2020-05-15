# Tareas
Como ejecutar tareas en nodeJS?

# Como crear una tarea ?

~~~
"scripts:{
    "nombreTarea":"node ubicacionArchivo.js"
}"
~~~

# Como correr una tarea ?

~~~
npm run nombreTarea
~~~

# Como ejecutar multiples tareas ?

> && sirve para poder unir cosas (Y)
>> Ej: node src/saludo.js && node src/despedida.js

~~~
"scripts:{
    "saludo":"node src/saludo.js",
    "despedida":"node src/despedida",
    "nombreTarea":"npm run saludo && npm run despedida"
}"
~~~
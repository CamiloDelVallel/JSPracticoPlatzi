### Escribe un código en JavaScript que le pregunte a los usuarios cuánto es 2 + 2. Si responden bien, mostramos un mensaje de felicitaciones, pero si responden mal, volvemos a empezar.

```js
let respuesta = prompt("cuánto es 2 + 2")
sumar(respuesta)

function sumar(respuesta){
    if (respuesta == 4 || respuesta == "cuatro"){
        return alert("felicitaciones")
    } else {
        alert("volvemos a empezar")
        return respuesta = prompt("cuánto es 2 + 2") + sumar(respuesta)
    }
}
```
### 2️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima su primer elemento.

```js

let array = []
function objeto(array){
    console.log(array[0])
}
```
### 3️⃣ Crea una función que pueda recibir cualquier array como parámetro e imprima todos sus elementos uno por uno (no se vale imprimir el array completo).

```js
let arrays = []
function objetos(arrays){
    for (let i = 0; i < array.length; i++) {
        const element = array[i];
        console.log(array[i])
    }
}
```

# testjspuro
# el código se puede probar en: 

```
https://playcode.io/new/
```
# Ejercicio 
Una función que recibe un arreglo de palabras y una palabra debe retornar un arreglo con la cantidad de veces que aparece esa palabra en el arreglo y el largo del arreglo
Al llamarla con (["ab","a"], "a") debería retornar [1,2]


```
let arregloLetras = (arr, letra) =>{
 
 let result = arr.includes(letra)
 let conteo = 0
 let total = []

 if(result){
 
   for(let i = 0; i < arr.length; i++){
     if(letra == arr[i]){
       conteo++
     }
   }

   total.push(conteo, arr.length)

  return console.log(total)
 }else {
    return console.log("No hay coincidencias")
 }

 
} 

arregloLetras(["ab","a"], "a")
```

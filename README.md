# testjspuro

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

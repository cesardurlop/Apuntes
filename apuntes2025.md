# Python 
## Estilos de texto

Configurar en negrita: **negrita**, __negrita__ <** **> o <__ __>  
Configurar en cursiva: *cursiva* <* *>  
Configurar subrayado: This is an <ins>underlined</ins> text    
poner un comentario con ">texto"
>este es un comentario  
Asi se resalta algo `hola`  

Para poner una lista se hace de la sig manera (con 3 comillas invertidas al inicio y final del texto)
```
esta  
es una   
lista   
```  
Puede crear un vínculo en línea escribiendo su texto entre corchetes [ ] y escribiendo la URL entre paréntesis ( ). También puede usar el método abreviado de teclado Command+K para crear un vínculo. Cuando haya seleccionado texto, puede pegar una dirección URL del Portapapeles para crear automáticamente un vínculo a partir de la selección.  
por ejemplo:
[(https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)] `Link para aprender mas sobre markdown `  

## REPASO EJERCICIOS PYTHON
Ejercicio: Define una clase llamada Persona.  
Inicializa los atributos nombre y edad.  
Agrega un metodo saludar
```
class Persona: 
      
     def __init__(self,nombre, edad):
            self.nombre =nombre
            self.edad = edad
     def saludar(self):
        print(f"Hola, mi nombre es {self.nombre} y tengo {self.edad} años.")

persona1= Persona("César",24)

persona1.saludar()  
``` 

```
git add -u  
esto es para agregar los cambios a la zona de preparacion  

Una vez que hayas añadido los cambios, puedes hacer un commit para registrar esos cambios:

git commit -m "Eliminados archivos innecesarios"      
  

Finalmente, si todo está listo y quieres reflejar las eliminaciones en tu repositorio remoto, puedes hacer un git push:

git push origin main


   

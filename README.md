### JS
~~~
multiparadigma , de tipado debil(quiere decir que un variable puede cambiar el tipo de datos sin problemas) y dinamico (js tiene tipos, detecta el tipo de variable automaticamente  )
~~~
### Variables = guardamos diferentes tipod de datos 
~~~
var / let / const
let : podemos reasignar la varible, la variable se queda en el scope
var : podemos acceder desde fuera de un scope 
 ~~~

### Tipos de datos
###### primitivos (que son inmutables, no se pueden cambiar los valores, cuando le aplicamos un metodo como toUpperCase(para ponerlo en mayuscula) lo que hace el metodo es devolver un nuevo string con el cambio )
~~~
string
numericos
booleanos
null
undefined

bigInt
Symbol
~~~

### Estructura de datos 
~~~
array/list []
     const libros = ["alicia en el pais", "frankestains]
          accedemos a los datos a traves de su indice que comienza en 0 
          libro[0]      y esto devolveria alicia en el pais
     
objetos {} clave/valor
     const persona = {
     name:"Mateo"
     apellido:"Gutierrez"}
               accedemos con el punto 
               persona.name     y esto devolveria Mateo
      
funcion 
      const sumar = (parametro1, parametro2) => {
      console.log (operador1, this)
      }
      
      console.log(sumar (1))      esto devolveria 1this
~~~

### Metodos
~~~
concat
map

~~~

## REACT JS
~~~
instalar node js para trabar con react js
node js
    npm  viene por defecto y es un gestor de paquetes de dependencias  
    npx  descarga en una carpeta temporal y lo ejecuta 
    
    
    para empezar nuestro proyecto, abirmos la consola y nos ubicamos donde queremos crear nuestra carpeta(en windows ls es dir) luego ejecutamos npx create-react-app name-app
    luego nos ubicamos en cd name-app
    y ejecutamos npm start 
    se nos abrira una pagina en el navegador y todo lo que desarollemos en react estara alojado en el localhost 3000
    https://es.reactjs.org/docs/create-a-new-react-app.html#create-react-app

abrimos la carpeta y vscode y nos apareceran varias carpetas
public -> para archivos estaticos
scr -> donde estara nuestro codigo fuente


componenentes1

function App() {
  const mensaje = "mundo2"
  return (
    <div className="App">
     hola {mensaje}
    </div>
  );
}

componentes 2 
const Mensaje2 = () => {
return <h1> hola mundo</h1>
}

function App() {
  const mensaje = "mundo2"
  return (
    <div className="App">
     hola {mensaje}
     <Mensaje2 />
    </div>
  );
}
**** CREAR COMPONENTES FUERA DE OTROS COMPONENTES (DEBEN ESTAR SEPARADOS)
**** Publicar app en github pages

extensiones : ESLint / Error Lens
~~~



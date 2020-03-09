# Porque Svelte ? 🚀

_A comparacion de los demas frameworks como Vue, React y Angular, Svelte es un Framework Pre compilado y usa Rollup.js como bundler para el tema del manejo de los paquetes de modulos._


## Estructura del Proyecto ⚙️

_Como archivos principales tenemos a :_

```
Public
```

_Donde va estar ubicados nuestros archivos estaticos._


```
src
```

_En este directorio es donde vamos a implementar nuestros componentes._


```
src/main.js
```

_Como archivo principal tenenmos a "main.js", que sera el corazon de nuestro proyecto, donde nosotros importamos el componente App, notese que todo componente creado en svelte tiene la extension ".svelte"._

_Lo primero que hacemos es crear una variable "app" donde nosotros instanciamos y le decimos que va a ser del tipo "App" y le pasamos dos parametros._

_El primero es el "target" que es donde se va a renderizar el componente._

_El Segudo es props que es el conjunto de propiedades que puede tener un componente, en este caso el prop que le pasamos es name y que tiene de valor "world"._


```
src/App.svelte
```

_Ya dentro del componente App.svelte, lo primero que vemos es que esta definido de la siguiente forma._

_<script></script> Donde va estar la parte logica del componete y la definicion de sus props, states y metodos del componente._

_Y antes de poder seguir explicando, la ventaja de crear componentes en svelte es que no te restringen a que pongas un tag html como padre, que es en el caso de los demas framework(Vue y React) que te obligan que tengas un tag html padre definido en tu componente. "eso no pasa con svelte"._

_Seguido de script esta <main></main> donde esta definido la parte sintactica de nuestro componente._

_y por ultimo esta <style></style> es aqui donde nosotros definiremos los estilos de nuestro componente._
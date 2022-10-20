# React 

## clases de ES6

```js
class App extends React.Component {
}
```

## render()

El método render retorna una descripción de lo que quieres ver en la pantalla. React toma la descripción y muestra el resultado

```js
class App extends React.Component {
  render() {
      return (
          //...
      );
  }
}
```

## return 

```js
class App extends React.Component {
  render() {
    return <h1>Hello world!</h1>
  }
}
```

Finalmente, usaremos el `render()` método React DOM para representar la clase `App` que creamos en el `root div` en nuestro HTML.

```js
ReactDOM.render(<App />, document.getElementById('root'))
```

## JSX: JavaScript + XML
Con JSX, podemos escribir lo que parece HTML y también podemos crear y usar nuestras propias etiquetas similares a XML. Así es como se ve JSX asignado a una variable.

```js
const heading = <h1 className="site-heading">Hello, React</h1>
```

Sin JSX 

```js
const heading = React.createElement('h1', { className: 'site-heading' }, 'Hello, React!')

```

## Componentes

Componente Simple

```js
const SimpleComponent = () => {
  return <div>Example</div>
}
```

Componente de Clase

```js
class ClassComponent extends Component {
  render() {
    return <div>Example</div>
  }
}
```

## Props
Un componente acepta parámetros, llamados props (abreviatura de “propiedades”)


## Estado
## Envío de datos del formulario
## Extrayendo datos de la API
## Creación e implementación de una aplicación React

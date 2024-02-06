- son argumentos, los cuales son utilizados por los componentes, el uso de props es lo mas comundo, estos son utilizados como un objeto 
  ```javascript
  function saludo(props){
    return <h1>¡Hola, {props.nombre}! </h1>;
  }
  ```
	- el uso de props solo es posible de padre a  hijo, es decir de componentes que depende de uno, en una sola via, de componente padre o contenedor a componente hijo o construido
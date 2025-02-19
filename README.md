A02 - Listas React Native 
# FlatList

## ¿Qué es FlatList?
Es un componente que optimiza el renderizado de listas de gran volumen de datos en la interfaz.

## Características de FlatList
Sus características son numerosas, pero se enfocan principalmente en el apartado visual para un mejor renderizado.   
A continuación, se presentan algunas de sus características más importantes:
- Es un componente multiplataforma.
- Soporte para modo horizontal.
- Carga de elementos al desplazarse.
- Soporte para varias columnas.
- Soporte para actualización en tiempo real de los elementos en lista.

## ¿Cómo funciona?
~~~
const App = () => (
  <FlatList
    data={DATA}
    renderItem={renderItem}
    keyExtractor={item => item.id}
  />
);
~~~
- data: Esta propiedad recibe un array de datos que permite renderizar los elementos de la lista.

- renderItem: Define cómo se renderiza cada uno de los elementos en la lista. 

- keyExtractor: Muestra cómo debe tomarse la clave de cada elemento de la lista. 
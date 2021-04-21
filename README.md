# Gestionamiento de insumos

<img alt='demo1' src='https://i.ibb.co/8mFpqrF/insumos.gif' width='600px'> 

## Qué es esta app

Esta herramienta fue desarrollada plenamente en un archivo HTML (**con CSS y JS embebido allí**) a pedido del cliente _Yangisee Insumos_, quien necesitaba un programa que le permitiera mantener una lista de los productos que vende y de los pedidos que realizaran sus clientes en base a dichos productos. A fines de simplificar la autogestión por parte del cliente y considerando que la cantidad de información es muy poca, opté por un **approach client-side**: la base de datos (tratándose en este caso de un JSON que contiene un objeto por cada producto y su información) está integrada en el archivo único, de forma tal que es accesible y modificable por el propio sin cliente sin necesidad de la intervención de servidores externos para almacenar la información. El guardado de los pedidos actúa de forma similar, dado que hice uso del LocalStorage para poder almacenar allí un objeto por cada pedido. Otros componentes, como la librería jQuery, fueron agregados a través de un CDN a fines de preservar la misma filosofía. La webapp, en rigor, le provee al usuario un entorno sencillo, ameno, ligero y comprensible de realizar tareas que de lo contrario serían mucho más técnicas, costosas y complejas. Resumidamente, el cliente podrá manejar el inventario de productos con su respectiva información de precio y atributos, agregar, borrar y modificar pedidos que integren dichos productos.

## Descargar

La app de Gestionamiento de insumos se puede bajar manualmente desde la web de Github o haciendo uso del siguiente comando en una terminal:

```
git clone https://github.com/ryaben/gestionamiento-insumos.git
```

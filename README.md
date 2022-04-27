# Reformar para usar otro Framework - Sails

## Validaciones:

### Insertamos el primer producto
#### POST
#### URL: http://localhost:1337/productos
~~~
{
    "title":"Producto 01",
    "price":"1500",
    "thumbnail":"https://pcsystemo.com/wp-content/uploads/2016/04/pcsystemo-productos-2.jpg"
}
~~~

### Insertamos el segundo producto
#### POST
#### URL: http://localhost:1337/productos
~~~
{
    "title":"Producto 02",
    "price":"500",
    "thumbnail":"https://pcsystemo.com/wp-content/uploads/2016/04/pcsystemo-productos-2.jpg"
}
~~~

### Consultamos el listado de productos
#### GET
#### URL: http://localhost:1337/productos

### Actualizamos el producto con Id 1
#### PUT
#### URL: http://localhost:1337/productos/1
~~~
{
    "title":"Producto FF",
    "price":"5500",
    "thumbnail":"https://pcsystemo.com/wp-content/uploads/2016/04/pcsystemo-productos-2.jpg"
}
~~~

### Eliminamos el producto con Id 1
#### DELETE
#### URL: http://localhost:1337/productos/1

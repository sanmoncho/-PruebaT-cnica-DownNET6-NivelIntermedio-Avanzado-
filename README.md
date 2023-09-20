# Prueba Técnica .NET 6 (Nivel Intermedio-Avanzado)

## Instrucciones Generales

¡Hola,  🚀 Prepárate para el desafío .NET 6 de tu vida (o al menos del día). Antes de empezar, asegúrate de estar en un lugar tranquilo y bien iluminado. También, prepárate para compartir tu pantalla; esta sesión será grabada.

- Clona este repositorio y que comiencen los juegos.
- Tienes 1 hora para completar las tareas. Sí, solo una hora, así que no hay tiempo para paseos por el parque.
- Haz un "push" de tu código antes de que el reloj marque el final.

## Tareas

### Tarea 1: Windows Forms con .NET 6 (20 minutos)

Abre el proyecto `WindowsFormsApp`. Implementa un formulario que permita al usuario ingresar su nombre, edad y una lista de habilidades (puede ser un conjunto de checkboxes). Al hacer clic en "Guardar", valida los datos y guárdalos en un archivo `.json`.

### Tarea 2: WPF con .NET 6 (20 minutos)

Abre el proyecto `WPFApp`. Utiliza el patrón MVVM para implementar las siguientes funcionalidades:

1. **Modelo**: Crea una clase `Producto` con propiedades como `Nombre`, `Precio` y `Cantidad`.

2. **ViewModel**: 
    - Crea una clase `ProductoViewModel` que contenga una colección observable de productos.
    - Implementa comandos para añadir, eliminar y editar productos.
    - Implementa una propiedad para filtrar productos por nombre.

3. **Vista**: 
    - Utiliza un `DataGrid` para mostrar la lista de productos.
    - Añade botones para las acciones de añadir, eliminar y editar, y enlázalos a los comandos en tu ViewModel.
    - Implementa un cuadro de búsqueda para filtrar los productos por nombre, enlazado a tu ViewModel.

Recuerda que la lógica de negocio debe estar en el ViewModel, y la Vista solo debe encargarse de la presentación y la interacción del usuario.

### Tarea 3: SQL Server (20 minutos)

Utiliza el archivo `database.sql` para crear una tabla llamada `Pedidos`. Escribe una consulta SQL para insertar un nuevo pedido con múltiples productos. Escribe una consulta SQL para actualizar el estado de un pedido. Escribe una consulta SQL para obtener todos los pedidos que incluyan un producto específico y que estén en un estado "Enviado".

## Criterios de Evaluación

- **Funcionalidad**: ¿El código hace lo que se supone que debe hacer?
- **Calidad del código**: ¿Es el código limpio, bien estructurado y fácil de entender?
- **Eficiencia**: ¿Se ha completado la tarea en el tiempo asignado?
- **Manejo de errores**: ¿Se manejan adecuadamente los casos de error?


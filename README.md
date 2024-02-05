## **Ejercicio de practica java:**

## lenguajes:

- MySQL
- Java

### **Contexto:**

Para este laboratorio se debe simular un almacén de piezas de automóviles donde cada pieza es esencial para diferentes procesos de mantenimiento y reparación de vehículos.

Piezas:

Las piezas pueden ser elementos como:

- Filtros de aceite
- Neumáticos
- Bujías
- Frenos
- Baterías, etc.

Cada una con características específicas como:

**Detalle de las piezas:** 

* **Identificador Único (ID):** Un número o código que identifica inequívocamente la pieza. Este identificador debe ser autoincremental asignado por el aplicativo.

* **Nombre:** Nombre descriptivo de la pieza (por ejemplo, "Filtro de Aceite Premium").

* **Categoría:** Tipo de pieza (como "Eléctrica", "Mecánica", "Hidráulica"). Esta categoría debe ser definida como una enumeración que posee características y comportamientos específicos.

* **Cantidad Disponible:** Número de unidades disponibles en el almacén.

**Tareas a Desarrollar:**

**1. Modelado de Piezas:**

* Crear una clase Pieza con los atributos mencionados.

* Crea las clases y/o interfaces necesarias para complementar la simulación del almacén de piezas.

**2. Otras abstracciones:**

* Se deben poder gestionar piezas que estén compuestas por otras piezas.

**3. Sistema de Gestión:**

* Implementar métodos para añadir nuevas piezas, eliminar piezas por ID, buscar piezas por nombre o categoría, y actualizar la cantidad de una pieza existente.

**4. Elección de Estructura de Datos:**

* Se debe decidir qué estructura de datos usar (por ejemplo, ArrayList, HashMap) basándose en la eficiencia para las operaciones de búsqueda, inserción y eliminación.

**5. Pruebas:**

* Implementar un menú completo y funcional que interactúe con el usuario por consola que permita probar todas las funcionalidades del aplicativo y que solo termine el programa cuando el usuario indique.
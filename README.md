•	Principio de Responsabilidad Única (SRP)

En el desarrollo de este deber se aplicó el Principio de Responsabilidad Única separando claramente las responsabilidades de cada clase. Cada clase fue diseñada para cumplir una única función dentro del sistema, evitando que una misma clase se encargue de múltiples tareas. Esta aplicación permitió mejorar la legibilidad del código y facilitó su mantenimiento, ya que cualquier cambio requerido afecta únicamente a la clase responsable y no al sistema completo. El principal problema que se resolvió con este principio fue el acoplamiento excesivo y la dificultad para identificar errores o realizar modificaciones sin generar efectos colaterales.

•	Principio de Abierto/Cerrado (OCP)

El Principio de Abierto/Cerrado se aplicó diseñando las clases de forma que puedan extenderse sin necesidad de modificar su código fuente. Esto se logró mediante el uso de abstracciones e interfaces, permitiendo agregar nuevas funcionalidades o comportamientos sin alterar las clases existentes. Gracias a este principio, el sistema se vuelve más flexible y escalable, evitando la necesidad de reescribir código probado. El problema principal que se resolvió fue la rigidez del sistema ante cambios o ampliaciones futuras.

•	Principio de Sustitución de Liskov (LSP)

Durante la implementación se respetó el Principio de Sustitución de Liskov asegurando que las clases hijas puedan sustituir a las clases padre sin alterar el comportamiento esperado del sistema. Las subclases implementan correctamente los contratos definidos por las clases base o interfaces, garantizando coherencia y confiabilidad. Este principio permitió evitar comportamientos inesperados al utilizar polimorfismo y resolvió problemas relacionados con herencias incorrectas que podían generar errores en tiempo de ejecución.

•	Principio de Segregación de Interfaces (ISP)

El Principio de Segregación de Interfaces se aplicó dividiendo las interfaces en contratos más pequeños y específicos, evitando que las clases implementen métodos que no utilizan. Esto permitió que cada clase dependa únicamente de las operaciones que realmente necesita, haciendo el código más limpio y comprensible. El principal problema que se resolvió fue la existencia de interfaces demasiado grandes que obligaban a implementar métodos innecesarios, aumentando la complejidad y el riesgo de errores.

•	Principio de Inversión de Dependencias (DIP)

Finalmente, el Principio de Inversión de Dependencias se aplicó haciendo que las clases de alto nivel dependan de abstracciones y no de implementaciones concretas. Esto se logró mediante el uso de interfaces y la inyección de dependencias, reduciendo el acoplamiento entre los componentes del sistema. Gracias a este principio, el código se vuelve más fácil de probar, mantener y extender. El problema principal que se resolvió fue la dependencia directa entre clases, lo que dificultaba los cambios y las pruebas unitarias.


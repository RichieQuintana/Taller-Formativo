**Descripcion del proyecto**

Este proyecto es un sistema de gestión de vehículos que incluye patrones de diseño Builder y Singleton para gestionar y organizar vehículos de manera eficiente. El sistema está diseñado para ser flexible, mantenible y escalable, y para satisfacer los requisitos de una única instancia de vehículo y la creación de objetos complejos.

***Estructura del proyecto***

project/ 
├── src/ 

│ ├── singleton_vehicle.py # Implementation of the Singleton pattern for unique vehicles 

│ ├── vehicle_builder.py # Implementation of the Builder pattern for flexible vehicle construction 

│ ├── home_page.py # Main client class integrating both patterns 

│ └── vehicle.py # Vehicle class representing the final product 

├── tests/ 

│ ├── test_singleton.py # Unit tests for Singleton implementation 

│ ├── test_builder.py # Unit tests for Builder implementation 

│ └── test_integration.py # Integration tests for combined functionality 

├── README.md # Project documentation 

└── requirements.txt # Dependencies

***Patrones de diseño utilizados***

**Patrón Singleton**

Propósito: garantizar una única instancia compartida de un modelo de vehículo específico.

**Implementación:**

La clase SingletonVehicle utiliza un atributo estático privado _instance para almacenar la única instancia.

Los clientes utilizan el método set_vehicle para configurar y recuperar la instancia.

**Patrón Builder**

Propósito: construir objetos Vehicle complejos paso a paso, lo que permite la personalización y una fácil extensión.

**Implementación:**

VehicleBuilder proporciona métodos como set_model, set_color y set_property para configurar el vehículo.

El método build devuelve una instancia Vehicle completamente construida.

Cómo ejecutar el proyecto

**Clonar el repositorio:**
https://github.com/RobertoArmas/Udla-Workshop-Design-Patterns/tree/master/DesignPatterns

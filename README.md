# backlog

### 10. Crear en el tenant central Market B2C.

Habilitar en el tenant central el Ecommerce, de modo que si un usuario desde su tenant, pueda habilitar que uno de sus productos sea visible en el Ecommerce del tenant central. 

### 10. Asegurar sea customizable el Ecommerce de los tenants. [Optional]

Cada usuario del Odoo SaaS debe poder cambiar la apariencia del ecommerce propio del tenant.

### 9. Lanzar el Odoo SaaS con Docker en AWS

revisar la variante de Daniel y actualizarla.

O evaluar alguna variante alternativa. 

Esto incluye comprar el certificado wild card para soportar multiples dominios.

### 8. Posibilidad de asociar un metodo de pago con los tenants.

Incialmente puede ser con paypal, luego se pueden habilitar otros tipos de pagos.

### 7. Por cada tenant en Odoo, autenticar en Cenit y crear un tenant.

Revisar los cambios que hizo Daniel para la version de OSSE.

Las funcionalidades deden incluir:

* Se lanza un tenant (instancia de Odoo) por cada cliente que se suscribe al SaaS.
* NO usar planes de servicios todos en principio con un mismo plan,
* Administración de la solución SaaS desde un Odoo central,  
* Los módulos requeridos son incluidos en la plantilla de la base de datos que se utiliza para crear nuevo tenant, de manera que aparecen pre-instalado cuando un clientese crea una nueva cuenta en el servicio SaaS.
* Acceso desde un tenant central para auditar los tenants de los clientes.
* Cada tenant nuevo en Odoo queda automáticamente conectado a un tenant homólogo en Cenit IO.

### 6. Instalar local SaaS en Odoo 10

Basado en el repo [odoo-saas-tool](https://github.com/it-projects-llc/odoo-saas-tools)


### 5.definir clasificacion facetada para la navegacion en el ecommerce

empezar con algo basico, pero que permita poco a poco ir adicionando nuevos taxons a las facetas que vayamos definiendo.

la idea es que los clientes finales puedan facilmente filtrar por mas de una categoria al mismo tiempo, y de ese modo poder incrementar la cantidad y tipoos de los productos, manteniendo la navegacion sencilla.


### 4. Definir Dominio y Comprar ssh para dominio

para poder comprar el certicado hay qeu tener primero el domini.

propongo cenit.market


### 2. Instalar Odoo en AWS, Ubuntu 16.04, RDS

ssh local


### 1. Probar la comunicacion Cenit.

Es importante que a traves de de Cenit se puedan hacer por parte de los clientes  todas las operaciones de gestion relativa con sus productos.

- gestionar productos,
- gestionar inventario.
- revisar las ordenes creadas.
 
# done

[pasar para aca las tareas que vayan quedando listas]


### 6. Crear en el tenant centrar market b2c.

Habilitar en el tenant central el Ecommerce, de modo que si un usuario desde su tenant, pueda habilitar que uno de sus productos sea visible en el Ecommerce del tenant central. 

### 5. Asegurar sea customizable el Ecommerce de los tenants. [Optional]

Cada usuario del Odoo SaaS debe poder cambiar la apariencia del ecommerce propio del tenant.

### 4. Lanzar el Odoo SaaS con Docker en AWS

revisar la variante de Daniel y actualizarla.

O evaluar alguna variante alternativa.  

### 3. Posibilidad de asociar un metodo de pago con los tenants.

Incialmente puede ser con paypal, luego se pueden habilitar otros tipos de pagos.

### 2. Por cada tenant en Odoo, autenticar en Cenit y crear un tenant.

Revisar los cambios que hizo Daniel para la version de OSSE.

Las funcionalidades deden incluir:

* Se lanza un tenant (instancia de Odoo) por cada cliente que se suscribe al SaaS.
* NO usar planes de servicios todos en principio con un mismo plan,
* Administración de la solución SaaS desde un Odoo central,  
* Los módulos requeridos son incluidos en la plantilla de la base de datos que se utiliza para crear nuevo tenant, de manera que aparecen pre-instalado cuando un clientese crea una nueva cuenta en el servicio SaaS.
* Acceso desde un tenant central para auditar los tenants de los clientes.
* Cada tenant nuevo en Odoo queda automáticamente conectado a un tenant homólogo en Cenit IO.

### 1. Instalar local SaaS en Odoo 10

Basado en el repo [odoo-saas-tool](https://github.com/it-projects-llc/odoo-saas-tools)
 

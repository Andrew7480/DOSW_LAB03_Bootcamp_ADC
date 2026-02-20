# Requerimientos Bankify

## Requerimientos seleccionados
### Funcionales

**Inicio de sesión**: Los opperadores y clientes deben autentificarse con 
usuario y contraseña para ingresar al sitio web del start up.

**Gestión de clientes**: Los operadores y supervisores pueden crear, activar, 
desactivar y actualizar información del cliente.

**Gestion de cuentas por supervisores**: Los supervisores pueden crear, eliminar, inactivar y actualizar la informacion 
de la cuenta de un cliente. 

**Gestion de cuentas por clientes**: Los clientes pueden inactivar su cuenta bancaria.

**Consulta de saldo**: Los clientes pueden consultar el saldo de su cuenta Bankify.

**Depositos**: Los clientes pueden hacer depositos a cuentas de si mismos o cuentas de otros 
usuarios.

**Reportes tributarios del cliente**: Los clientes pueden generar reportes 
tributarios de declaracion de renta.

**Reportes tributarios del gerente financiero**: Los gerentes pueden generar reportes sobre 
todas las cuentas creadas para agentes como la DIAN.

**Eliminacion de cuentas**: Los supervisores pueden eliminar clientes y sus cuentas asociadas.

### No Funcionales

**Numero de cuenta**: Al momento de crear una cuenta, el numero de esta cuenta debe tener exactamente 10
digitos, solamente numeros, ninguna letra o caracter especial.

**Banco asocioados**: En el numero de cuenta, los dos primeros dijitos deben corresponder a el banco del cual 
estan asociados, dentro de los bancos asociados al StartUp.

**Bancos activos**: Una cuenta se puede crear unicamente sobre bancos registrados en el sistema del StartUp.

**Reportes a clientes**: Al momento de generar un reporte tributario a un cliente, este debe generarse en fotmato 
PDF para mayor comprension del lector.

**Reportes a la DIAN**: Al momento de generar un reporte tributario a la DIAN, este debe generarse en formato JSON.

## Diagramas de casos de uso

### Primer requerimiento

**Gestión de clientes**: Los operadores y supervisores pueden crear, activar,
desactivar y actualizar información del cliente.

Anexo
![](/docs/uml/funcional1.png)

No. f01_SyC

Dentro de los roles del operador y supervisor, los cuales tienen control completo sobre el start up, 
les permiten crear la cuenta de donde el usuario puede interactuar con la aplicacion, asi pues estos roles 
pueden crear la cuenta de un cliente, activarla y desactivarla de acuerdo a politicas de inactividad u otras cauas, 
ademas de actializar informacion de una cuenta por si se requiere por parte del cliente.

## Segundo requerimiento

**Depositos**: Los clientes pueden hacer depositos a cuentas de si mismos o cuentas de otros
usuarios.
Anexo
![](/docs/uml/funcional2.png)
No. f02_d

Los clientes de la aplicacion de Bankify, pueden hacer depositos a la cuenta activa de un cliente, 
estos depositos los pueden hacer tanto el mismo propietario de la cuenta como una cuenta externa, facilitando 
asi el envio de dinero de una cuenta a otra.

## Tercer requerimiento

**Gestion de cuentas por supervisores**: Los supervisores pueden crear, eliminar, inactivar y actualizar la informacion
de la cuenta de un cliente.

Anexo
![](/docs/uml/funcional3.png)

El rol de supervisor, ante las cuentas de los usuarios o clientes de la Star up, puede manejarla 
de tal manera que pueden crear cuentas bancarias, eliminarlas y actualiar la información de esta, 
asi manejamos la integridad de las cuentas evitando que los clientes y evitando que estos puedan crear 
infinitas cuentas.

# Preguntas Finales


# CuentaBancaria
<p>
  Este programa implementa una simulación básica de una cuenta bancaria en Java. Vamos a analizarlo en detalle:

Características principales
Datos del cliente y cuenta bancaria:

Se inicializan con valores predeterminados:
nombre: "Tony Stark".
tipoDeCuenta: "Corriente".
saldo: 1599.99.
Menú interactivo:

Utiliza un bucle while para mantener activo el menú hasta que el usuario seleccione la opción de salir (9).
Las opciones del menú incluyen:
Consultar saldo.
Retirar dinero.
Depositar dinero.
Salir del programa.
Interacción con el usuario:

Se usa un objeto Scanner para capturar la entrada del usuario desde el teclado.
Las opciones seleccionadas son manejadas mediante una estructura switch-case.
Operaciones bancarias:

Consultar saldo: Simplemente muestra el saldo actual.
Retirar dinero: Verifica si el saldo es suficiente antes de realizar la operación.
Depositar dinero: Suma el monto ingresado al saldo actual.
</p>

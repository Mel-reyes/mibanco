# Desafío - Always Music
## Descripción
En este desafío validaremos nuestros conocimientos de Transacciones, Captura de errores
en transacciones. 
## Tecnologías Utilizadas
- NODE
## Requerimientos
1. Crear una función asíncrona que registre una nueva transferencia utilizando una
transacción SQL. Debe mostrar por consola la última transferencia registrada.
(3 Puntos)
2. Realizar una función asíncrona que consulte la tabla de transferencias y retorne los
últimos 10 registros de una cuenta en específico.
(3 Puntos)
3. Realizar una función asíncrona que consulte el saldo de una cuenta en específico.
(2 Puntos)
4. En caso de haber un error en una transacción SQL, se debe retornar el error por
consola.
(2 Puntos)
## Instrucciones
Orden de argumentos: node index.js <tipo_transaccion> <cuenta_origen> <fecha> <descripcion> <monto> <cuenta_destino>
  1. Nueva transacción:  Ejemplo: node index.js nueva 1 "02/05/2024" "transaccion 1" 56500 2
  2. Consulta de últimas transferencias para la cuenta 1 Ejemplo: node index.js consulta 1
  3. Consulta de saldo para la cuenta 1 Ejemplo: node index.js consulta-saldo 1




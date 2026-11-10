## Resumen de cambios

Explicacion concisa de lo que este pull request introduce, corrige o modifica.

## Issue vinculada

Closes #

## Tipo de cambio

- [ ] Nueva funcionalidad
- [ ] Correccion de error (Bug fix)
- [ ] Refactorizacion de codigo
- [ ] Herramientas o configuracion

## Como probar localmente

Instrucciones paso a paso para que el revisor verifique los cambios en su entorno local Laragon:

1. Obtener y cambiar a la rama correspondiente.
2. Aplicar cambios en base de datos si corresponde.
3. Acceder al punto de entrada local: `http://localhost/...`
4. Verificar el comportamiento esperado.

## Lista de verificacion para la revision entre pares

- [ ] El codigo respeta los estandares PER-CS (`composer run-script cs:check`).
- [ ] El analisis estatico no reporta errores en nivel 8 (`composer run-script analyse`).
- [ ] El formato de codigo cumple las reglas de Prettier (`npm run format:check`).
- [ ] La compilacion de activos frontend no arroja advertencias (`npm run build`).
- [ ] Se probo localmente en Windows con Laragon (PHP 8.3, MySQL 8.4).
- [ ] No se incluyeron credenciales, secretos ni archivos de depuracion temporales.
- [ ] La rama se encuentra sincronizada con develop antes de fusionar.

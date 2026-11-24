# Serviexpert — Demo web

Demo estática e interactiva para presentar el flujo de un taller de reparación de computadoras.

## Publicar en GitHub Pages
1. Crea un repositorio público llamado `serviexpert-demo` (o el nombre que prefieras).
2. Sube `index.html` a la raíz del repositorio.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona `main` y `/ (root)`, y guarda.
6. Espera a que GitHub Pages publique el sitio.

## Qué incluye
- Panel principal con indicadores.
- Clientes: crear y buscar registros.
- Recepción de equipos y creación de órdenes.
- Seguimiento y cambio de estados.
- Caja y registro de ingresos ficticios.
- Inventario y ventas de muestra.
- Diseño adaptable a móvil y escritorio.

## Importante
Es una demostración frontend. Los registros viven en la memoria de la página y se reinician al recargar. No tiene backend, autenticación, base de datos, pagos ni persistencia. No ingresar información real de clientes. La versión productiva deberá conectarse al VPS/API y a MySQL.

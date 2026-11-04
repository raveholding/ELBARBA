# El Barba · Menú digital

Menú público de **El Barba — Sándwiches y Pizzas** (Barrio Pereyra Rozas, Salta), hecho con Sistema VB.

- Un solo archivo: `index.html` (funciona sin servidor; las fotos y el logo van incluidos).
- Categorías: Promos, Burgers Smash, Hamburguesas (simple/doble), Sándwiches, Pizzas y Al plato.
- Buscador, carrito y pedido por WhatsApp (retiro o envío a domicilio), indicador «Abierto ahora» (martes a domingos, 21:00 a 1:00 hs).
- `og.jpg`: imagen que se ve al compartir el link por WhatsApp o redes.

## Cómo cambiar precios o productos
Abrí `index.html` y buscá `var ITEMS = [` (productos y precios) y `var BIZ = {` (número de WhatsApp, horarios y dirección del mapa). Cada producto tiene `name`, `desc`, `img` (opcional) y `opts` con el precio.

## Publicar
GitHub → Settings → Pages → *Deploy from a branch* → `main` / `/ (root)`. Queda en `https://raveholding.github.io/ELBARBA/`.

---
Desarrollado por **VINCULAR BUSINESS** · (387) 4484132 · vincularbusiness@gmail.com · «Tu idea, en buenas manos.»

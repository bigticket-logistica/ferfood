# FerFood

App para darle comida al perro desde el celular, con un dispensador de cartón, un ESP32 y un servo.

- La app (este repositorio) se publica en Vercel.
- Al apretar "Dar comida", se crea un pedido en Supabase.
- El ESP32 revisa Supabase cada 2 segundos, abre la compuerta y marca el pedido como servido.

Proyecto de ciencia hecho en familia.

# IABasicaGrafos

## Cambios en la escena `TanksWaypoints`

He añadido una nueva zona llamada **Puesto Norte** (`PostoNorte`) y la he conectado con `WP002`, `WP007` y `WP008` mediante enlaces de doble sentido. Así, desde la roca (`WP002`) hay dos rutas posibles hasta el puesto: una directa y otra que pasa por `WP007`.

También he añadido el botón **Ir ao Posto Norte**. Al pulsarlo, el tanque utiliza el algoritmo A* para calcular una ruta desde su waypoint actual hasta el puesto y la recorre hasta llegar al destino.

## Cómo probarlo

1. Abre `Assets/Scenes/TanksWaypoints.unity` en Unity y pulsa **Play**.
2. Pulsa **Ir ao Posto Norte** y observa cómo el tanque llega al nuevo waypoint.
3. Pulsa **Go to Ruin** para recorrer la conexión entre el puesto y las ruinas (`WP008`).
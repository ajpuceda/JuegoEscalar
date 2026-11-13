# 🧗 Escalador

Juego de escalada en muro hecho con HTML, CSS y JavaScript puro (un solo archivo, sin dependencias). Piensa como un escalador de verdad: elige **qué mano o pie soltar** y **dónde colocarlo** sin perder el equilibrio ni agotarte.

▶️ **Jugar:** abre `index.html` en el navegador, o activa **GitHub Pages** (Settings → Pages → rama `main`, carpeta `/root`).

## Cómo se juega

1. Pulsa **1–4** (o los botones) para elegir la extremidad que quieres soltar:
   - `1` Mano izquierda · `2` Mano derecha · `3` Pie izquierdo · `4` Pie derecho · `Esc` cancelar
2. Haz clic en una **presa dentro del círculo de alcance** para colocarla ahí.
3. Solo puedes mover **una extremidad a la vez**: mientras tanto, tu cuerpo depende de las otras tres.

## No caigas

- **Centro de gravedad:** debe quedar dentro del triángulo de apoyo formado por las extremidades ancladas. Si sales, aparece un anillo de advertencia que se cierra — recoloca rápido o caerás.
- **Resistencia:** cada movimiento gasta energía. Las **regletas** agotan más, las **placas** son menos estables, las presas verdes de **descanso** y las **repisas** te recuperan. Sin fuerza = caída.
- **Checkpoints:** las repisas grandes guardan tu progreso. Si caes, vuelves a la última que hayas superado.

## Objetivo

Llegar a la **cima 🏁** (≈ 49 m). Cada partida genera una ruta distinta con el botón *Nueva ruta*; tu mejor altura se guarda en el navegador.

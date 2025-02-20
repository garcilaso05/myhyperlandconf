# myhyperlandconf

Este repositorio contiene la configuración personalizada para el gestor de ventanas Hyprland en Arch Linux. El archivo principal de configuración es hyprland.conf, el cual debe ser guardado en el directorio `~/.config/hypr`.

## Contenido del archivo hyprland.conf

### Reglas de Ventanas Flotantes

El archivo de configuración define reglas específicas para que ciertas aplicaciones se abran en modo flotante. Algunas de estas aplicaciones incluyen:

- `python3`
- `kamoso`
- `mpv`
- `org.gnome.Calculator`
- `io.github.josephmawa.Bella`
- `org.gnome.Solanum`
- `dev.edfloreshz.Tasks`
- `ca.vlacroix.Tally`
- `re.sonny.Retro`
- `io.github.nokse22.trivia-quiz`
- `org.gnome.Calendar`

### Atajos de Teclado

El archivo contiene una variedad de atajos de teclado para mejorar la productividad. Algunos de los atajos más interesantes incluyen:

- **Abrir terminal**: `SUPER + Q`
- **Cerrar ventana activa**: `SUPER + C`
- **Ejecutar Firefox**: `SUPER + F`
- **Cambiar fondo aleatorio**: `SUPER + M`
- **Ejecutar script de programas**: `SUPER + E`
- **Captura de pantalla**: `Print` o `SUPER + Print`
- **Reproducir sonidos frikis**: `Alt + Q` (y otros)
- **Easter Egg**: `SUPER + F11` (reproduce un video de Grievous)

### Plugins

El archivo de configuración también incluye varios plugins para mejorar la funcionalidad de Hyprland:

- **dynamic-cursors**: Modifica el comportamiento del cursor basado en la velocidad y dirección del movimiento.
- **hyprfocus**: Añade animaciones de enfoque para ventanas flotantes y cambios de espacio de trabajo.
- **hy3**: Configura el comportamiento de las pestañas y el autotiling.

### Personalizaciones de Estilo y Formato

El archivo hyprland.conf contiene varias personalizaciones de estilo y formato, tales como:

- **Gaps y bordes**: Configuración de espacios internos y externos, tamaño de bordes y colores.
- **Decoraciones**: Redondeo de esquinas, habilitación de desenfoque y configuraciones de sombras.
- **Animaciones**: Definición de animaciones para ventanas, bordes y transiciones de espacios de trabajo.

### Ejecución de Aplicaciones al Inicio

El archivo también define aplicaciones que se ejecutan automáticamente al iniciar Hyprland, como `waypaper`, `waybar`, `nm-applet` y `blueman-applet`.

## Instalación

Para utilizar esta configuración, copia el archivo hyprland.conf en el directorio `~/.config/hypr`:

```sh
cp hyprland.conf ~/.config/hypr/
```

## Enlaces Útiles

- [Documentación de Hyprland](https://wiki.hyprland.org/)
- [Reglas de Ventanas](https://wiki.hyprland.org/Configuring/Window-Rules/)
- [Configuración de Monitores](https://wiki.hyprland.org/Configuring/Monitors/)
- [Variables de Configuración](https://wiki.hyprland.org/Configuring/Variables/)
- [Atajos de Teclado](https://wiki.hyprland.org/Configuring/Binds/)

Esta configuración está personalizada por Roger García Doncel (garcilaso05).
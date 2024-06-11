# NeoVim Config

Esta es la configuración que tengo para NeoVim.

## Como Instalar y Configurar NeoVim.

Instalación de NeoVim:

GNU/Linux
Arch Linux `sudo pacman -Syu neovim`

Instalar dependencias y paquetes necesarios:

Arch Linux `sudo pacman -Syu nodejs npm`

- Cambia al directorio de `.config`.
`cd ~/.config`

- Clonar el repositorio de la Configuración.
`git clone "https://github.com/anderon-2201/nvim"`

Ejecuta `nvim` en tu terminal o lanzador de aplicaciones.

En NeoVim presiona `:` escribe `PlugInstall` y presiona Enter.

Ejecuta `:` escribe `quit` y presiona Enter.

Cambia al directorio `~/.config/nvim/vim-plug.coc.nvim` y ejecuta.
`npm ci`

> [!WARNING]
> Si en dado caso aparece error:
> Ejecuta `npm audit fix` y vuelva a ejecutar `npm ci` nuevamente

Ahora ejecuta `nvim` para instalar con `:CocInstall coc-clangd` y `:CocInstall coc-python` para el autocompletado para los lenguajes C y Python.

POr ultimo, ejecuta `:TransparentEnable` para que NeoVim sea transparente.

¡Y listo!

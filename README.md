# NeoVim Config

Esta es la configuración que tengo para NeoVim.

## Como Instalar y Configurar NeoVim.

Instalación de NeoVim:

- GNU/Linux
Arch Linux
```bash
sudo pacman -Syu neovim
```

Instalar paquetes necesarios:

- Arch Linux 
```bash
sudo pacman -Syu nodejs npm
```

- Cambia al directorio de `.config`.
```bash
cd ~/.config
```

- Clonar el repositorio de la Configuración.
```bash
git clone "https://github.com/anderon-2201/nvim"
```

Ejecuta `nvim` en tu terminal o lanzador de aplicaciones.

En NeoVim presiona `:` escribe `PlugInstall` y presiona Enter.

Ejecuta `:` escribe `quit` y presiona Enter.

- Cambia al directorio.
```bash
~/.config/nvim/vim-plug/coc.nvim
```

- Y ejecuta.
```bash
npm ci
```

> [!WARNING]
> Si en dado caso aparece error de `high severity vulnerability`:
> - Ejecuta el siguiente comando `npm audit fix` y vuelva a ejecutar `npm ci` nuevamente

Ahora ejecuta `nvim` para instalar con.
```bash
:CocInstall coc-clangd
```
```bash
:CocInstall coc-python
```
Para el autocompletado para los lenguajes C y Python.

Por ultimo, ejecuta `:TransparentEnable` para que NeoVim tenga fondo transparente.

¡Y listo!

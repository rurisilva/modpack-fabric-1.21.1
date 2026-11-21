# Modpack Fabric 1.21.1

78 mods, Fabric Loader, Minecraft 1.21.1, Java 21. Gestionado con [packwiz](https://packwiz.infra.link/).

## Jugadores (Prism Launcher)
1. Crea una instancia de Minecraft 1.21.1 con Fabric.
2. Descarga `packwiz-installer-bootstrap.jar` de https://github.com/packwiz/packwiz-installer-bootstrap/releases y ponlo en la carpeta de la instancia.
3. En Editar instancia → Configuración → Personalizado → Comandos → *Pre-launch command*:
   `"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/rurisilva/modpack-fabric-1.21.1/main/pack.toml`
4. Al abrir el juego se descargan y actualizan los mods solos.

## Administrar
- Añadir: `packwiz mr add <slug>` · Actualizar: `packwiz update --all` · Quitar: `packwiz remove <slug>`
- Después: `git commit` y `git push`; los jugadores se actualizan al abrir el juego.

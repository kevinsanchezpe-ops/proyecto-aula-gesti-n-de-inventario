# HighSport - Sistema de Gestion de Inventario Deportivo

Proyecto academico para la materia de Interfaces. Esta entrega corresponde a la fase de desarrollo visual del sistema para una marca de ropa deportiva, tomando como base el mockup aprobado en Figma y aplicando principios de UI/UX.

## Descripcion

HighSport es una propuesta de interfaz para un sistema de inventario de un almacen deportivo. El proyecto presenta el flujo visual de gestion de usuario y gestion de productos dentro de un entorno moderno, oscuro y deportivo.

En esta fase se implementaron las pantallas principales del sistema en HTML y CSS, con navegacion entre vistas y una identidad visual consistente.

## Modulos incluidos

- Inicio de sesion
- Panel general del sistema
- Inventario de productos
- Registro de usuarios
- Registro de nuevos productos
- Edicion de productos

## Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts

## Estructura del proyecto

```text
proyecto aula/
|-- index.html
|-- panel.html
|-- dashboard.html
|-- registro-usuario.html
|-- nuevo-producto.html
|-- editar-producto.html
|-- styles.css
|-- README.md
`-- img/
    |-- fondo.png
    |-- botaroja.png
    `-- guayo-rojo.png
```

## Descripcion de archivos

- `index.html`: pantalla de inicio de sesion
- `panel.html`: dashboard o panel general con resumen del sistema
- `dashboard.html`: modulo de inventario con tabla de productos
- `registro-usuario.html`: formulario para creacion de usuarios
- `nuevo-producto.html`: formulario para registrar productos
- `editar-producto.html`: formulario para editar productos
- `styles.css`: hoja de estilos general del proyecto

## Requisitos para ejecutarlo en Windows

Para visualizar el proyecto correctamente en Windows se necesita:

- Windows 10 o Windows 11
- Un navegador web actualizado:
  - Google Chrome
  - Microsoft Edge
  - Mozilla Firefox

No es necesario instalar base de datos ni dependencias externas, ya que esta entrega corresponde a una implementacion front-end estatica.

## Guia de instalacion y ejecucion en Windows

### Opcion 1: Apertura directa

1. Descarga o clona el repositorio desde GitHub.
2. Si el proyecto fue descargado en `.zip`, descomprime la carpeta.
3. Abre la carpeta del proyecto en Windows.
4. Ingresa al archivo `index.html`.
5. Haz doble clic sobre `index.html` para abrirlo en el navegador.

### Opcion 2: Ejecucion con Visual Studio Code

1. Instala [Visual Studio Code](https://code.visualstudio.com/).
2. Abre la carpeta del proyecto desde VS Code.
3. Abre el archivo `index.html`.
4. Ejecuta el proyecto abriendo el archivo en tu navegador.

### Opcion 3: Ejecucion con Live Server

1. Instala Visual Studio Code.
2. Ve a la seccion de extensiones.
3. Busca la extension **Live Server** e instalala.
4. Haz clic derecho sobre `index.html`.
5. Selecciona **Open with Live Server**.

## Navegacion del sistema

El recorrido principal del sistema es el siguiente:

1. El usuario ingresa desde `index.html`.
2. Luego accede a `panel.html`, donde observa el resumen general del sistema.
3. Desde el panel puede navegar a `dashboard.html` para consultar el inventario.
4. Tambien puede dirigirse a `registro-usuario.html` para visualizar la gestion de usuarios.
5. Desde inventario puede ir a `nuevo-producto.html` o `editar-producto.html`.

## Caracteristicas visuales

- Estilo basado en el mockup aprobado en Figma
- Paleta institucional en negro, blanco y rojo
- Interfaz consistente entre modulos
- Formularios visuales para gestion de usuarios y productos
- Tabla de inventario con acciones de editar y eliminar
- Panel general con resumen de metricas y accesos rapidos
- Diseno responsive basico para diferentes tamanos de pantalla

## Alcance de esta entrega

Esta version corresponde a la fase de maquetacion e interfaz del sistema. Por lo tanto, incluye:

- Prototipo visual implementado en HTML y CSS
- Navegacion entre pantallas
- Representacion visual del CRUD de inventario
- Gestion visual de usuario
- Guia de despliegue en Windows

Actualmente no incluye:

- Conexion a base de datos
- Inicio de sesion real
- Persistencia de informacion
- CRUD funcional con logica en JavaScript o backend

## Autor

Proyecto desarrollado por Kevin Julian Sanchez Perez para entrega academica del proyecto de aula de Interfaces.

# Gifs-app 💠

## Descripción general 📌
Gifs-app es una aplicación web para buscar, visualizar y gestionar GIFs de forma rápida, accesible y visualmente agradable. Ofrece una interfaz responsiva e intuitiva que permite a los usuarios encontrar animaciones mediante palabras clave, previsualizarlas y acceder a opciones para guardarlas o compartirlas fácilmente.

## Características principales ✨
- 🔍 Búsqueda por palabras clave con resultados relevantes y filtrado.
- 🖼️ Previsualización de GIFs con reproducción automática o control manual.
- ⭐ Guardado de favoritos para acceso rápido y gestión personal.
- 📤 Compartir enlaces directos o copiar URL al portapapeles.
- 📱 Diseño responsivo y accesible para dispositivos móviles y escritorio.
- ⚙️ Integración configurable con APIs públicas de GIFs (por ejemplo, Giphy o Tenor).

## Beneficios y objetivos 🎯
- Facilitar el descubrimiento de contenido animado de manera eficiente.
- Proveer una experiencia de usuario clara, rápida y ligera.
- Ofrecer una arquitectura extensible que permita agregar nuevas fuentes, filtros o funcionalidades con facilidad.

## Tecnologías 🧩
- Frontend: React
- Lenguaje: TypeScript
- Bundler / Dev server: Vite
- Plugins recomendados en el proyecto:
  - `@vitejs/plugin-react` (usa Babel para Fast Refresh)
  - `@vitejs/plugin-react-swc` (usa SWC para Fast Refresh)
- Transpiladores / Herramientas: Babel o SWC (según plugin elegido)
- Linter: ESLint (configuraciones tipo TypeScript sugeridas en el README)
- Runtime / Herramientas de desarrollo: Node.js
- Gestores de paquetes: npm / yarn

## Instalación y ejecución (ejemplo) 🚀
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/XxJorge1xX/Gifs-app.git
   ```
2. Instalar dependencias:
   ```bash
   npm install
   # o
   yarn install
   ```
3. Ejecutar en modo desarrollo:
   ```bash
   npm start
   # o
   yarn start
   ```

## Configuración de la API 🔐
- Añadir la clave de la API del proveedor de GIFs (por ejemplo, `GIPHY_API_KEY`) en las variables de entorno o en el archivo de configuración según la estructura del proyecto.

https://forobatman.netlify.app/
# Documentación Técnica — Gotham City Web

## 1. Introducción
Gotham City Web es una aplicación web desarrollada con Astro, dedicada a la exploración del universo de Batman y la ciudad de Gotham. El proyecto integra información de la Batman API y presenta una experiencia visual moderna, interactiva y educativa.

## 2. Objetivos
- Ofrecer una plataforma informativa y visual sobre Gotham, Batman y sus personajes.
- Implementar buenas prácticas de desarrollo web con Astro y componentes reutilizables.
- Integrar datos externos mediante API y mostrar contenido dinámico.

## 3. Estructura del Proyecto

```
Pagina_web_astro/
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── public/
├── src/
│   ├── assets/         # Imágenes y recursos gráficos
│   ├── components/     # Componentes Astro reutilizables
│   ├── layouts/        # Layout global del sitio
│   └── pages/          # Páginas principales del sitio
└── README.md
```

### src/components/
- **BackButton.astro**: Botón de navegación.
- **FilterBar.astro**: Barra de filtros para personajes.
- **GadgetCard.astro**: Card para gadgets.
- **PersonajeCard.astro**: Card para personajes.
- **SectionTitle.astro**: Título de sección.
- **ThemeCard.astro**: Card para temas.

### src/pages/
- **index.astro**: Página de inicio.
- **batman.astro**: Perfil de Batman, integración con Batman API.
- **batman-temas.astro**: Temas principales (psicología, simbolismo, ética).
- **personajes.astro**: Listado y filtro de personajes (aliados y enemigos).
- **gadgets.astro**: Arsenal de gadgets.
- **historia.astro**, **gotham.astro**, **mapa-gotham.astro**, **etica.astro**, **psicologia.astro**, **simbolismo.astro**: Páginas temáticas.

### src/layouts/
- **Layout.astro**: Estructura global, cabecera, navegación y pie de página.

## 4. Tecnologías y Dependencias

- **Astro** (framework principal)
- **HTML5, CSS3**
- **Animaciones CSS**
- **Integración API externa** ([Batman API](https://batmanapi.com/doc/batman-api/))

## 5. Descripción de Funcionalidades

- **Navegación principal**: Acceso rápido a todas las secciones relevantes.
- **Cards interactivas**: Para personajes y gadgets, con estilos y animaciones.
- **Filtro de personajes**: Permite visualizar aliados o enemigos.
- **Mapa de Gotham**: Página ilustrada con efectos visuales.
- **Temas y análisis**: Psicología, ética y simbolismo de Batman.

## 6. Estilo y Diseño

- Paleta de colores oscuros, dorados y azules.
- Glassmorphism, niebla y luces animadas.
- Diseño responsive y moderno.
- Animaciones en cards, títulos y mapa.

## 7. Ejecución y Desarrollo

### Instalación
```bash
npm install
```

### Ejecución en modo desarrollo
```bash
npm run dev
```

Abre tu navegador en [http://localhost:4321](http://localhost:4321) (o el puerto que indique Astro).

## 8. Buenas Prácticas y Recomendaciones

- Mantener componentes reutilizables y desacoplados.
- Usar estilos globales en el layout y específicos en cada componente.
- Documentar cada componente y página con comentarios claros.
- Validar la integración con la API y manejar errores.

## 9. Créditos y Licencia

Desarrollado para U-Tad, asignatura de desarrollo de aplicaciones web.
Integración con [Batman API](https://batmanapi.com/doc/batman-api/).

---


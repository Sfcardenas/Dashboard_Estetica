# Base Dashboard

## Descripción

Base es un dashboard administrativo diseñado para un sistema operativo SaaS orientado a clínicas estéticas, salones premium y centros de bienestar.

La interfaz fue construida con un enfoque moderno tipo enterprise dashboard, priorizando:

- claridad visual,
- velocidad de navegación,
- escalabilidad,
- accesibilidad,
- diseño responsive,

El dashboard incluye:

- sidebar de navegación colapsable,
- métricas operacionales,
- inteligencia de conversión,
- alertas predictivas,
- tablas operacionales,
- microinteracciones visuales,
- y componentes reutilizables.

El objetivo del proyecto es simular una interfaz SaaS moderna inspirada en plataformas como:

- Linear,
- Notion,
- Stripe Dashboard,
- Fresha,
- Attio,
- Raycast.

---

# Tecnologías Usadas

## HTML5

Se utilizó HTML5 semántico para mejorar:

- accesibilidad,
- SEO,
- estructura del documento,
- compatibilidad con lectores de pantalla.

Elementos semánticos utilizados:

```html
<header>
  <nav>
    <main>
      <section>
        <table>
          <footer></footer>
        </table>
      </section>
    </main>
  </nav>
</header>
```

---

## CSS3

El sistema visual fue construido completamente en CSS puro utilizando:

- CSS Variables (Custom Properties),
- Flexbox,
- CSS Grid,
- Media Queries,
- Pseudo-clases,
- Transiciones,
- Estados interactivos.

Características principales:

- Design Tokens mediante `:root`
- Layout responsive
- Sidebar mobile expandible
- Microinteracciones
- Sistema de spacing consistente
- Sistema de sombras y superficies
- Scrollbars customizados

---

## JavaScript Vanilla

Se utilizó JavaScript puro para:

- apertura/cierre del menú mobile,
- manejo del overlay,
- interacciones básicas del sidebar.

No se utilizaron frameworks externos.

---

# Decisiones de Diseño

## Sistema Visual

Se implementó un sistema visual minimalista y moderno basado en:

- superficies claras,
- contraste elevado,
- sombras suaves,
- bordes sutiles,
- espaciado consistente,
- y tipografía limpia.

El dashboard utiliza una arquitectura visual inspirada en productos SaaS enterprise modernos.

---

## Layout

La estructura principal utiliza:

- CSS Grid para la distribución general,
- Flexbox para alineaciones internas,
- responsive design mobile-first.

El sidebar se transforma en un menú overlay en dispositivos móviles.

---

## Componentización

La nomenclatura CSS sigue una metodología tipo BEM:

```css
.sidebar__brand
.alert-card__title
.nav__link--active
```

Esto mejora:

- mantenibilidad,
- escalabilidad,
- legibilidad,
- reutilización de componentes.

---

# Accesibilidad

El proyecto incorpora múltiples prácticas de accesibilidad:

## Navegación por teclado

Se añadieron estados:

```css
:focus-visible;
```

para:

- botones,
- enlaces,
- elementos interactivos.

---

## HTML Semántico

Se utilizaron etiquetas semánticas para mejorar:

- navegación asistida,
- interpretación del contenido,
- estructura accesible.

---

## Contraste Visual

Los colores fueron seleccionados para mantener buen contraste entre:

- texto,
- fondos,
- badges,
- estados operacionales.

---

## Responsive Design

El dashboard se adapta a:

- desktop,
- tablet,
- mobile.

Incluyendo:

- sidebar colapsable,
- tablas con scroll horizontal,
- reducción progresiva de contenido secundario.

---

# Características Destacadas

- Sidebar responsive expandible
- Dashboard analytics moderno
- Funnel de conversión visual
- Alertas predictivas
- Microinteracciones premium
- Hover states avanzados
- Sistema de variables CSS
- Arquitectura escalable
- Diseño responsive
- Accesibilidad básica implementada

---

# Mejoras Futuras

Posibles mejoras futuras del proyecto:

- Dark Mode
- Sistema de temas dinámicos
- Charts reales con librerías
- Integración API
- Animaciones avanzadas
- Persistencia del estado del sidebar
- Dashboard en tiempo real
- Componentización con React/Vue
- Design System completo
- Tokens centralizados

---

# Autor

Sebastián Cárdenas

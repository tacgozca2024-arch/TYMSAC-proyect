# TYMSAC — Landing Page Corporativa

> Sitio web profesional para **Transporte y Maniobras S.A.C.**, empresa peruana de transporte pesado y logística industrial.

🔗 **[Ver proyecto en vivo] (https://tacgozca2024-arch.github.io/TYMSAC-proyect/)**

---



## Descripción

Landing page moderna desarrollada desde cero para TYMSAC, empresa con más de 15 años de experiencia en transporte de carga pesada, maniobras industriales y logística integral en el Perú.

El diseño está inspirado en la identidad visual real de la empresa: paleta de colores **cian eléctrico, negro y acero**, con el motivo de rayas horizontales tomado directamente de la fachada del local.

---

## Secciones

- **Hero** — Encabezado animado con speed lines en canvas y estadísticas clave
- **Servicios** — 6 tarjetas de servicios con hover effects
- **Nosotros** — Historia, valores y año de fundación
- **Flota** — Unidades operativas con barras de capacidad
- **Contacto** — Formulario con validación y estado global
- **Footer** — Información de contacto y enlaces

---

## Stack tecnológico

| Herramienta | Uso |
|---|---|
| React 18 | UI framework |
| Vite 5 | Build tool y dev server |
| Context API + useReducer | Estado global |
| CSS por componente | Estilos modulares |
| GitHub Pages | Hosting |

---

## Características técnicas

- ✅ Componentes reutilizables y limpios
- ✅ Estado global con Context API (formulario, menú, sección activa)
- ✅ `useScrollSpy` con `IntersectionObserver` para nav activo
- ✅ Animaciones CSS + canvas (`requestAnimationFrame`)
- ✅ Diseño responsive (mobile, tablet, desktop)
- ✅ Accesibilidad básica (aria-labels, roles, motion-reduce)

---

## Instalación local

```bash
# 1. Clonar el repositorio
git clone https://github.com/tacgozca2024-arch/TYMSAC-proyect.git

# 2. Entrar a la carpeta
cd TYMSAC-proyect

# 3. Instalar dependencias
npm install

# 4. Correr en desarrollo
npm run dev
```

---

## Paleta de colores

| Token | Color | Uso |
|---|---|---|
| `--cyan` | `#00B4D8` | Acento principal, CTAs |
| `--black` | `#0D0D0D` | Fondo principal |
| `--steel` | `#1E2730` | Secciones alternas |
| `--white` | `#F5F7F9` | Texto principal |
| `--gray` | `#8A9BAB` | Texto secundario |

---

## Desarrollado por

**Adolfo** — Frontend Developer  
Proyecto freelance para cliente real · 2026

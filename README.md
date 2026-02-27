# 🌐 Portfolio Personal — Next.js 15

> **Portfolio full-stack con animaciones 3D, Supabase y diseño premium**

[![Demo en Vivo](https://img.shields.io/badge/Demo-Live-green?style=flat-square&logo=vercel)](https://dfbportfolio.vercel.app)
![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs)
![Spline](https://img.shields.io/badge/Spline_3D-FF4D4D?style=flat-square&logo=spline&logoColor=white)
![Framer](https://img.shields.io/badge/Framer_Motion_11-0055FF?style=flat-square&logo=framer&logoColor=white)

---

## 🌐 Demo en vivo

**👉 [dfbportfolio.vercel.app](https://dfbportfolio.vercel.app)**

---

## 📋 Descripción

Portfolio profesional construido con **Next.js 15** y un sistema de diseño "Liquid Luxury" — glassmorphism, dark mode, animaciones 3D con Spline y micro-interacciones con Framer Motion. Integra Supabase para formulario de contacto y datos dinámicos.

### Características principales

- ✅ **Escena 3D interactiva** con Spline Design (`@splinetool/react-spline`)
- ✅ **Orb canvas animado** como fallback WebGL de alta performance
- ✅ **Animaciones fluidas** con Framer Motion 11 (scroll-triggered, hover effects)
- ✅ **Design system propio** — glassmorphism, dark mode, paleta HSL custom
- ✅ **Formulario de contacto** persistido en Supabase
- ✅ **Bilingüe** EN/ES con i18n
- ✅ **Lighthouse score 95+** — Core Web Vitals optimizados

---

## 🛠️ Stack Técnico

| Capa | Tecnología |
|---|---|
| **Framework** | Next.js 15 (App Router) |
| **Lenguaje** | TypeScript 5.x |
| **Estilos** | Tailwind CSS 4.x · Vanilla CSS |
| **Animaciones** | Framer Motion 11.x |
| **3D** | Spline Design · Canvas API |
| **Backend** | Supabase 2.x |
| **Deploy** | Vercel |

---

## 🏗️ Arquitectura

```
┌──────────────────────────────────────────┐
│           Next.js 15 App Router           │
│  ┌─────────┐  ┌──────────┐  ┌─────────┐  │
│  │  Hero   │  │Projects  │  │ Contact │  │
│  │ Spline  │  │  Cards   │  │  Form   │  │
│  │  3D     │  │ Framer   │  │         │  │
│  └─────────┘  └──────────┘  └────┬────┘  │
└─────────────────────────────────┼────────┘
                                  ▼
                    ┌─────────────────────┐
                    │   Supabase 2.x      │
                    │  Contact messages   │
                    └─────────────────────┘
```

---

> **Nota:** Este es un repositorio de exhibición. El código fuente del portfolio es privado.
> Para contacto o proyectos a medida: [diegofbis63@gmail.com](mailto:diegofbis63@gmail.com)

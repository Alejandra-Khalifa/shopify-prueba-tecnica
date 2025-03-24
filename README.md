Documento técnico

# 🛍️ Prueba Técnica - Shopify Frontend Developer

**Demo URL:** https://unow-prueba-tecnica-frontend-developer.myshopify.com/?_ab=0&_fd=0&_sc=1  
**Repositorio:** [GitHub](https://github.com/Alejandra-Khalifa/shopify-prueba-tecnica)

https://unow-prueba-tecnica-frontend-developer.myshopify.com/
clake: Khalifa2025

---

## 📋 Descripción del Proyecto

Implementación de un tema Shopify basado en el diseño Figma proporcionado, cumpliendo con los criterios de **maquetación Pixel Perfect**, optimización de rendimiento y buenas prácticas de desarrollo.

### 🔑 Entregables Principales

- Maquetación responsiva con **Flexbox/CSS Grid**.
- Lazy Loading para imágenes/assets.

---

## 🛠️ Configuración del Entorno

### Requisitos Previos

- Node.js v18+
- Shopify CLI v3.0+
- Cuenta en [Shopify Partners](https://partners.shopify.com/)

### Instalación

```bash
# Clonar repositorio
git clone https://github.com/Alejandra-Khalifa/shopify-prueba-tecnica
cd prueba-shopify

# Instalar dependencias
npm install

# Vincular proyecto a la tienda Shopify
shopify theme dev --store=tu-tienda.myshopify.com

theme/
├── src/
│   ├── assets/            # SCSS, JS compilados
│   ├── config/            # settings_schema.json
│   ├── layout/            # theme.liquid
│   ├── sections/          # Bloques reutilizables
│   ├── templates/         # Páginas personalizadas
│   └── locales/           # Traducciones
│
├── .gitignore
├── package.json
└── README.md

se creó en  assets el archivo de estilos: assets/custom-styles.css.liquid

.banner__text p {
  color: var(--Gray-200, #eaecf1);

  color: var(--Gray-200, color(display-p3 0.9181 0.926 0.9419));
  text-align: center;
  /* Text md/Semibold */
  font-family: Inter;
  font-size: 16px;
  font-style: normal;
  font-weight: 600;
  line-height: 24px; /* 150% */
}

.banner__heading {
  color: var(--Base-White, #fff);
  color: var(--Base-White, color(display-p3 1 1 1));
  text-align: center;
  font-family: "Inter", sans-serif;
  font-size: 72px;
  font-style: normal;
  font-weight: 600;
  line-height: 90px;
  letter-spacing: -1.44px;
}

/* Primer botón - Demo */
.banner__buttons--multiple a.button:nth-child(1) {
  border: 16px 12px 16px 28px;
  border-radius: 8px;
  border: 1px solid var(--Gray-300, #CCD5DF);
  border: 1px solid var(--Gray-300, color(display-p3 0.8144 0.8349 0.8656));
  background: var(--Base-White, #FFF);
  background: var(--Base-White, color(display-p3 1 1 1));

  /* Shadow/xs */
  box-shadow: 0px 1px 2px 0px rgba(14, 24, 41, 0.05);
  box-shadow: 0px 1px 2px 0px color(display-p3 0.0627 0.0941 0.1569 / 0.05);
  color: var(--Gray-700, #314155);

  color: var(--Gray-700, color(display-p3 0.2053 0.2525 0.328));
  /* Text lg/Semibold */
  font-family: Inter;
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  line-height: 28px; /* 155.556% */
}

/* Segundo botón - Sign up */
.banner__buttons--multiple a.button:nth-child(2) {
  border-radius: 8px;
  border: 1px solid var(--Blue-600, #0074FF);
  border: 1px solid var(--Blue-600, color(display-p3 0.0837 0.439 0.9363));
  background: var(--Blue-600, #0072F7);
  background: var(--Blue-600, color(display-p3 0.0837 0.439 0.9363));

  /* Shadow/xs */
  box-shadow: 0px 1px 2px 0px rgba(14, 24, 41, 0.05);
  box-shadow: 0px 1px 2px 0px color(display-p3 0.0627 0.0941 0.1569 / 0.05);

  color: var(--Base-White, #FFF);
  color: var(--Base-White, color(display-p3 1 1 1));

  /* Text lg/Semibold */
  font-family: Inter;
  font-size: 18px;
  font-style: normal;
  font-weight: 600;
  line-height: 28px; /* 155.556% */color: var(--Base-White, #FFF);
  color: var(--Base-White, color(display-p3 1 1 1));

}

/* Estilos hover para mejor interactividad */
.rich-text__buttons--multiple a.button:nth-child(1):hover {
  background: var(--Gray-50, #F8FAFC) !important;
}

.rich-text__buttons--multiple a.button:nth-child(2):hover {
  background: var(--Blue-700, #005FCC) !important;
}


#g63Ss3QwN- > div.gWVFPtV1pC.gp-relative.gp-flex.gp-flex-col > div > div > picture > img {
  width: 100% !important;
  height: 100% !important;
  object-fit: cover !important; /* Mantiene la relación de aspecto */
  aspect-ratio: 576/560 !important; /* Para navegadores modernos */
}
```

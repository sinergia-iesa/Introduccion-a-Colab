# Introducción a Python en Colab

Presentación hecha con [Slidev](https://sli.dev), réplica de la presentación
original (pptx) del curso, desplegada por su cuenta en GitHub Pages con
GitHub Actions.

Autor: MSI. Álvaro Mena Monge · 24 y 26 de febrero del 2026

Link: https://sinergia-iesa.github.io/Introduccion-a-Colab/
Repositorio: https://github.com/sinergia-iesa/Introduccion-a-Colab

## Publicar en GitHub Pages

1. Sube este proyecto a un repositorio de GitHub (rama `main`).
2. En el repositorio: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Cada `push` a `main` compila y publica la presentación en
   https://sinergia-iesa.github.io/Introduccion-a-Colab/. El `--base`
   (`/Introduccion-a-Colab/`) se arma solo a partir del nombre del repositorio
   (ver `.github/workflows/deploy.yml`), así que las rutas de imágenes y logos
   coinciden sin tocar nada.

## Desarrollo local

```bash
npm install
npm run dev      # abre la presentación en http://localhost:3030
npm run build    # genera dist/
```

Navegación: flechas del teclado o barra espaciadora.

## Estructura

- `slides.md`: las 6 diapositivas (texto y posiciones idénticos al pptx).
- `styles.css`: estilo de la presentación. El lienzo es de 1280 × 720 px, igual
  que el pptx, así que las medidas son las originales convertidas a px.
- `public/img/`: portada y capturas de las diapositivas.
- `public/logos/logos.png`: logos (UCR · SA-D Sede del Atlántico).
- `notebooks/`: los cuadernos del curso; las diapositivas los abren en Colab directo desde GitHub.
- `public/mlb.csv`: archivo de datos que se descarga desde la diapositiva.
- `global-bottom.vue`: número de página.

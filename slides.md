---
theme: default
layout: none
class: colab
title: Introducción a Python en Colab
info: |
  ## Introducción a Python en Colab
  MSI. Álvaro Mena Monge · 24 y 26 de febrero del 2026
canvasWidth: 1280
aspectRatio: 16/9
drawings:
  persist: false
transition: slide-left
colorSchema: light
---

<div class="colab-slide">
  <img class="colab-cover-bg" src="/img/portada.jpg" alt="" />
  <div class="colab-cover-scrim"></div>
  <img class="colab-cover-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE, Carrera de Informática Empresarial, Sede del Atlántico" />
  <div class="colab-cover-title" role="heading" aria-level="1">Introducción a Python en Colab</div>
  <div class="colab-cover-author">
    <p>MSI. Álvaro Mena Monge</p>
    <p>24 y 26 de febrero del 2026</p>
  </div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Google Colab</div>
  <p class="cx-lead">Google Colaboratory es un entorno de cuadernos Jupyter gratuito en la nube. Escribe y ejecuta Python directamente en tu navegador, con acceso gratuito a GPUs y TPUs. Ideal para Machine Learning, investigación y educación.</p>
  <div class="cx-h2" style="top:338px">Beneficios Clave.</div>
  <div class="cx-cards">
    <div class="cx-card"><div class="cx-card-ic"><svg viewBox="0 0 48 48"><path d="M24 4c8 5 12 14 11 24l-6 6H19l-6-6C12 18 16 9 24 4z" fill="#f9ab00"/><circle cx="24" cy="20" r="4.5" fill="#fff"/><path d="M13 26l-7 10 9-2zM35 26l7 10-9-2zM21 38h6l-3 8z" fill="#e8710a"/></svg></div><div><div class="cx-card-t">Cero Configuración.</div><div class="cx-card-d">Empieza a codificar en segundos. Python 2.7 y 3.6+ soportados por defecto.</div></div></div>
    <div class="cx-card"><div class="cx-card-ic"><svg viewBox="0 0 48 48"><g stroke="#f9ab00" stroke-width="3" stroke-linecap="round"><path d="M14 4v6M24 4v6M34 4v6M14 38v6M24 38v6M34 38v6M4 14h6M4 24h6M4 34h6M38 14h6M38 24h6M38 34h6"/></g><rect x="9" y="9" width="30" height="30" rx="4" fill="#f9ab00"/><rect x="17" y="17" width="14" height="14" rx="2" fill="#fff"/></svg></div><div><div class="cx-card-t">Aceleración de Hardware.</div><div class="cx-card-d">Acceso gratuito a GPUs y TPUs para entrenar modelos complejos.</div></div></div>
    <div class="cx-card"><div class="cx-card-ic"><svg viewBox="0 0 48 48"><rect x="8" y="6" width="30" height="34" rx="3" fill="#f9ab00"/><rect x="8" y="36" width="34" height="6" rx="3" fill="#e8710a"/><path d="M16 30V20M23 30V14M30 30V22" stroke="#fff" stroke-width="4" stroke-linecap="round"/></svg></div><div><div class="cx-card-t">Bibliotecas Pre-instaladas.</div><div class="cx-card-d">Pandas, NumPy, Scikit-learn y TensorFlow listas para usar.</div></div></div>
    <div class="cx-card"><div class="cx-card-ic"><svg viewBox="0 0 48 48"><circle cx="15" cy="16" r="6" fill="#f9ab00"/><path d="M4 36c0-7 5-10 11-10s11 3 11 10z" fill="#f9ab00"/><circle cx="37" cy="10" r="5.5" fill="#f9ab00"/><circle cx="37" cy="36" r="5.5" fill="#f9ab00"/><path d="M26 18l8-6M26 26l8 8" stroke="#e8710a" stroke-width="3.5" stroke-linecap="round"/></svg></div><div><div class="cx-card-t">Colaboración en Tiempo Real.</div><div class="cx-card-d">Funciona como Google Docs. Comparte y edita en equipo.</div></div></div>
  </div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Google Colab</div>
  <div class="cx-h2" style="top:196px;left:0;width:1280px;text-align:center;font-size:44px">La Solución: Jupyter en la Nube.</div>
  <div class="cx-eq">
    <div class="cx-eq-i"><div class="cx-jup"><i class="a1"></i><i class="a2"></i><span>jupyter</span><u style="left:6px;top:8px;width:16px;height:16px"></u><u style="right:0;top:0;width:18px;height:18px"></u><u style="left:34px;bottom:0;width:18px;height:18px"></u></div></div><div class="cx-op">+</div>
    <div class="cx-eq-i"><div class="cx-cloud"><i style="left:6px;top:64px;width:76px;height:76px"></i><i style="left:44px;top:20px;width:100px;height:100px"></i><i style="left:112px;top:56px;width:82px;height:82px"></i><i style="left:30px;top:84px;width:140px;height:56px;border-radius:0"></i><b>G</b></div></div><div class="cx-op">+</div>
    <div class="cx-eq-i"><svg width="150" height="150" viewBox="0 0 130 130"><g stroke="#e8710a" stroke-width="5" stroke-linecap="round"><path d="M35 6v14M55 6v14M75 6v14M95 6v14M35 110v14M55 110v14M75 110v14M95 110v14M6 35h14M6 55h14M6 75h14M6 95h14M110 35h14M110 55h14M110 75h14M110 95h14"/></g><rect x="20" y="20" width="90" height="90" rx="10" fill="#f37726"/><rect x="50" y="50" width="30" height="30" rx="4" fill="#fff"/></svg><span class="cx-cap">Hardware Gratuito</span></div><div class="cx-op">=</div>
    <div class="cx-eq-i"><svg width="190" height="100" viewBox="0 0 120 64"><path d="M44.6 14A22 22 0 1 0 44.6 50" fill="none" stroke="#f9ab00" stroke-width="13"/><path d="M75.4 50A22 22 0 1 0 75.4 14" fill="none" stroke="#e8710a" stroke-width="13"/></svg></div>
  </div>
  <p class="cx-lead" style="top:540px;font-size:32px;color:#1f2937">Un entorno de Jupyter Notebook gratuito que se ejecuta completamente en la nube. Escribe y ejecuta código Python directamente desde tu navegador.</p>
</div>
<!--
frece acceso gratuito a aceleración mediante GPU (Unidades de Procesamiento Gráfico) y TPU (Unidades de Procesamiento Tensorial)
-->

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Google Colab</div>
  <div class="cx-h2" style="top:190px;font-size:34px">El Entorno de Trabajo.</div>
  <div class="cx-mock">
    <div class="cx-mh"><svg class="cx-co" width="52" height="28" viewBox="0 0 120 64"><path d="M44.6 14A22 22 0 1 0 44.6 50" fill="none" stroke="#f9ab00" stroke-width="13"/><path d="M75.4 50A22 22 0 1 0 75.4 14" fill="none" stroke="#e8710a" stroke-width="13"/></svg><div><div class="cx-mf">Untitled0.ipynb <i>☆</i></div><div class="cx-mm"><span>File</span><span>Edit</span><span>View</span><span>Insert</span><span>Runtime</span><span>Tools</span><span>Help</span></div></div><div class="cx-mr"><span>Comment</span><span>Share</span></div></div>
    <div class="cx-mb"><span>+ Code</span><span>+ Text</span><em></em><span>Connect ▾</span><span>✎ Editing</span></div>
    <div class="cx-mbody"><div class="cx-cell"><span class="cx-play">▶</span></div></div>
    <b class="cx-bd" style="left:292px;top:10px">1</b><b class="cx-bd" style="left:330px;top:168px">2</b><b class="cx-bd" style="left:424px;top:78px">3</b>
  </div>
  <div class="cx-leg">
    <div><b class="cx-bd">1</b>Menú de Archivo y Título</div>
    <div><b class="cx-bd">2</b>Celdas de Código</div>
    <div><b class="cx-bd">3</b>Estado de RAM/Disco</div>
  </div>
  <div class="cx-note"><b>Archivos .ipynb:</b> Los notebooks se guardan automáticamente en una carpeta dedicada de Google Drive llamada "Colab Notebooks".</div>
  <div class="cx-libs">
    <div class="cx-lib cx-blue"><b>NumPy &amp; Pandas</b><span>Manipulación de Datos</span></div>
    <div class="cx-lib cx-violet"><b>TensorFlow &amp; Keras</b><span>Deep Learning</span></div>
    <div class="cx-lib cx-mint"><b>Matplotlib &amp; Seaborn</b><span>Visualización</span></div>
    <div class="cx-lib cx-peach"><b>Scikit-learn</b><span>Machine Learning Clásico</span></div>
  </div>
</div>
<!--
frece acceso gratuito a aceleración mediante GPU (Unidades de Procesamiento Gráfico) y TPU (Unidades de Procesamiento Tensorial)
-->

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Google Colab</div>
  <div class="cx-openrow"><a class="cx-btn" href="https://colab.research.google.com/" target="_blank" rel="noopener noreferrer">Abrir Google Colab ↗</a></div>
  <img src="/img/colab-notebook.png" style="left:313.5px;top:266px;width:653.2px;height:379.9px" alt="Notebook de Colab con una celda de código que ejecuta !python --version." />
  <svg class="colab-lines" viewBox="0 0 1280 720" xmlns="http://www.w3.org/2000/svg">
    <line x1="735.7" y1="625.3" x2="821.6" y2="659.1" stroke="#1f497d" stroke-width="0.84" />
    <line x1="430.1" y1="618.3" x2="397.7" y2="649.3" stroke="#1f497d" stroke-width="0.84" />
  </svg>
  <div class="colab-label" style="left:808.6px;top:667.2px">Celda</div>
  <div class="colab-label" style="left:355px;top:671.4px">Correr</div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Major League Baseball</div>
  <div class="cx-field">
    <svg viewBox="0 0 1160 510"><defs><clipPath id="cxw"><path d="M580 440L170 50Q580 -40 990 50Z"/></clipPath></defs>
      <rect width="1160" height="510" rx="14" fill="#2b5f2c"/>
      <path d="M580 440L170 50Q580 -40 990 50Z" fill="#3f8a3c" stroke="#fff" stroke-width="3" stroke-linejoin="round"/>
      <circle cx="580" cy="300" r="185" fill="#b98d5a" opacity=".55" clip-path="url(#cxw)"/>
      <polygon points="580,440 730,290 580,140 430,290" fill="#4c9a48" stroke="#fff" stroke-width="3"/>
      <g fill="#fff"><rect x="720" y="280" width="20" height="20" transform="rotate(45 730 290)"/><rect x="570" y="130" width="20" height="20" transform="rotate(45 580 140)"/><rect x="420" y="280" width="20" height="20" transform="rotate(45 430 290)"/><path d="M570 436h20v8l-10 8-10-8z"/></g>
    </svg>
    <div class="cx-pos" style="left:580px;top:30px"><b>CF</b> - Jardinero Central</div>
    <div class="cx-pos" style="left:580px;top:88px"><b>OF</b> - Jardineros</div>
    <div class="cx-pos" style="left:250px;top:120px"><b>LF</b> - Jardinero Izquierdo</div>
    <div class="cx-pos" style="left:910px;top:120px"><b>RF</b> - Jardinero Derecho</div>
    <div class="cx-pos" style="left:420px;top:185px"><b>SS</b> - Campocorto</div>
    <div class="cx-pos" style="left:740px;top:178px"><b>2B</b> - Segunda Base</div>
    <div class="cx-pos" style="left:300px;top:290px"><b>3B</b> - Tercera Base</div>
    <div class="cx-pos" style="left:580px;top:262px"><b>P</b> - Lanzador</div>
    <div class="cx-pos" style="left:860px;top:290px"><b>1B</b> - Primera Base</div>
    <div class="cx-pos" style="left:580px;top:330px"><b>SP</b> - Lanzador Abridor</div>
    <div class="cx-pos" style="left:1000px;top:360px"><b>RP</b> - Lanzador de Relevo</div>
    <div class="cx-pos" style="left:840px;top:425px"><b>DH</b> - Bateador Designado</div>
    <div class="cx-pos" style="left:580px;top:478px"><b>C</b> - Receptor</div>
  </div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Material: Introducción a Python</div>
  <div class="cx-fname">Parte1-Introduccion_python.ipynb</div>
  <p class="cx-desc">Cuaderno de introducción a la programación con Python: tipos de datos, booleans y type(), variables y asignación, strings, listas, control de flujo y ciclos (bucles) y funciones.</p>
  <div class="cx-linkbox"><a class="cx-btn" href="https://colab.research.google.com/github/sinergia-iesa/Introduccion-a-Colab/blob/main/notebooks/Parte1-Introduccion_python.ipynb" target="_blank" rel="noopener noreferrer">Abrir el cuaderno en Colab ↗</a></div>
  <div class="cx-copy" style="justify-content:center"><div class="cx-note2" style="max-width:860px">El cuaderno se abre directo desde GitHub. Para conservar tus cambios, <b>guarda una copia en tu Google Drive</b> (mira el tutorial de la diapositiva 10).</div></div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Material: NumPy</div>
  <div class="cx-fname">Parte2-NumPy.ipynb</div>
  <p class="cx-desc">Cuaderno sobre NumPy, la librería de álgebra lineal de Python: creación de arreglos y matrices, uso de len, arange y dtype, matrices de ceros y unos, y conversión de una matriz a DataFrame.</p>
  <div class="cx-linkbox"><a class="cx-btn" href="https://colab.research.google.com/github/sinergia-iesa/Introduccion-a-Colab/blob/main/notebooks/Parte2-NumPy.ipynb" target="_blank" rel="noopener noreferrer">Abrir el cuaderno en Colab ↗</a></div>
  <div class="cx-copy" style="justify-content:center"><div class="cx-note2" style="max-width:860px">El cuaderno se abre directo desde GitHub. Para conservar tus cambios, <b>guarda una copia en tu Google Drive</b> (mira el tutorial de la diapositiva 10).</div></div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Material: Pandas</div>
  <div class="cx-fname">Parte3-Pandas.ipynb</div>
  <p class="cx-desc">Cuaderno de manipulación de datos con Pandas: cargar mlb.csv en un DataFrame, consultar datos, seleccionar columnas, obtener valores únicos, agregar columnas calculadas y graficar salarios (distribución y promedio por equipo).</p>
  <div class="cx-linkbox"><a class="cx-btn" href="https://colab.research.google.com/github/sinergia-iesa/Introduccion-a-Colab/blob/main/notebooks/Parte3-Pandas.ipynb" target="_blank" rel="noopener noreferrer">Abrir el cuaderno en Colab ↗</a></div>
  <div class="cx-copy" style="justify-content:center"><div class="cx-note2" style="max-width:860px">El cuaderno se abre directo desde GitHub. Para conservar tus cambios, <b>guarda una copia en tu Google Drive</b> (mira el tutorial de la diapositiva 10).</div></div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Tutorial: guardar tu copia en Drive</div>
  <div class="cx-steps">
    <div class="cx-step"><b class="cx-bd">1</b><div>Abre el cuaderno con el botón <b>«Abrir el cuaderno en Colab»</b>.</div></div>
    <div class="cx-step"><b class="cx-bd">2</b><div>En el menú <b>Archivo</b> (File) elige <b>«Guardar una copia en Drive»</b> (Save a copy in Drive).</div></div>
    <div class="cx-step"><b class="cx-bd">3</b><div>Se abre una pestaña nueva con tu copia, llamada <b>«Copia de…»</b>. Trabaja siempre en esa pestaña.</div></div>
    <div class="cx-step"><b class="cx-bd">4</b><div>Tu copia queda en Google Drive, en la carpeta <b>«Colab Notebooks»</b>, y se guarda automáticamente.</div></div>
  </div>
  <div class="cx-note2 cx-stepnote">Si cierras la pestaña del original sin guardar una copia, <b>se pierden tus cambios</b>.</div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Datos: mlb.csv</div>
  <div class="cx-fname">mlb.csv</div>
  <p class="cx-desc">Archivo de datos que se usa en el cuaderno de Pandas: 867 jugadores de Major League Baseball, con las columnas NAME, TEAM, POS, SALARY, START_YEAR, END_YEAR y YEARS.</p>
  <div class="cx-linkbox"><a class="cx-btn" href="https://sinergia-iesa.github.io/Introduccion-a-Colab/mlb.csv" download="mlb.csv" target="_blank" rel="noopener noreferrer">Descargar mlb.csv ↓</a></div>
  <div class="cx-copy" style="justify-content:center"><div class="cx-note2" style="max-width:860px">Este archivo <b>no se copia</b>: solo se descarga a tu computadora. En la siguiente diapositiva aprenderás a subirlo a Colab.</div></div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Tutorial: subir un archivo a Colab</div>
  <div class="cx-steps">
    <div class="cx-step"><b class="cx-bd">1</b><div>Haz clic en <b>«Conectar»</b> (Connect), arriba a la derecha, para iniciar el entorno.</div></div>
    <div class="cx-step"><b class="cx-bd">2</b><div>Abre el panel de archivos con el ícono de <b>carpeta</b> de la barra lateral izquierda.</div></div>
    <div class="cx-step"><b class="cx-bd">3</b><div>Haz clic en el botón de <b>subir</b> (hoja con flecha hacia arriba) y elige el <b>mlb.csv</b> que descargaste.</div></div>
    <div class="cx-step"><b class="cx-bd">4</b><div>Verás <b>mlb.csv</b> en la lista de archivos. Ya está listo para usarse desde el cuaderno.</div></div>
  </div>
  <div class="cx-note2 cx-stepnote">Los archivos subidos son temporales: <b>se borran al terminar la sesión</b> de Colab. Si te desconectas, vuelve a subirlo.</div>
</div>

---
layout: none
class: colab
---

<div class="colab-slide">
  <div class="colab-banner"><img src="/img/portada.jpg" alt="" /></div>
  <img class="colab-logos" src="/logos/logos.png" alt="Universidad de Costa Rica · SA-CIE" />
  <div class="colab-title" role="heading" aria-level="1">Tutorial: leer el archivo con Pandas</div>
  <p class="cx-desc" style="top:205px">Con el archivo ya subido, Pandas lo lee usando su nombre. En el cuaderno de Pandas se hace así:</p>
  <pre class="cx-code">path = "mlb.csv"
mlb = pd.read_csv(path)
mlb.head()</pre>
  <div class="cx-steps" style="top:452px">
    <div class="cx-step"><b class="cx-bd">1</b><div>Ejecuta la celda con el botón <b>▶</b> (Correr).</div></div>
    <div class="cx-step"><b class="cx-bd">2</b><div>Verás una tabla con las primeras 5 filas: NAME, TEAM, POS, SALARY…</div></div>
  </div>
  <div class="cx-note2 cx-stepnote" style="top:620px">Si aparece <b>FileNotFoundError</b>, revisa que mlb.csv esté en el panel de archivos y que el nombre sea exacto.</div>
</div>

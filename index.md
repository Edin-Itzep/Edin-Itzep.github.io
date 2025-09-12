---
title: Portafolio de Edin
layout: default
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css?v=3' | relative_url }}">

<div class="hero">
  <h1>Hola, soy Edin 👋</h1>
  <p>Data Analyst en progreso. Amo <b>Power BI</b>, <b>Excel/Power Query</b> y voy por <b>Python</b>. Aquí muestro lo que sé hacer.</p>
  <div class="badges">
    <a href="https://www.linkedin.com/tu-perfil" target="_blank">LinkedIn</a>
    <a href="mailto:tu.correo@ejemplo.com" target="_blank">Email</a>
    <a href="https://github.com/Edin-Itzep" target="_blank">GitHub</a>
    <a href="/Edin-CV.pdf" target="_blank">Descargar CV</a>
  </div>
</div>

<div class="section">
  <h2>📊 Proyectos destacados</h2>

  <div class="grid">

    <div class="card">
      <h3>Grocery Shop – Dashboard de Ventas</h3>
      <p>Análisis de ventas por sucursal, crecimiento anual y productos más vendidos.</p>
      <iframe
        title="GroceryShop"
        width="100%" height="420"
        src="TU_SRC_COMPLETO"
        frameborder="0" allowfullscreen="true"></iframe>
    </div>

    <div class="card">
      <h3>Dashboard de Ventas</h3>
      <p>Análisis por región, producto y canal. Incluye YoY y top 10.</p>
      <p>
        <a class="btn primary" href="https://app.powerbi.com/view?r=LINK1" target="_blank">Abrir en Power BI</a>
        <a class="btn" href="/proyectos/ventas.md">Explicación</a>
      </p>
    </div>

    <div class="card">
      <h3>Atención al Contribuyente</h3>
      <p>Métricas de satisfacción, tiempos de respuesta y volumen por modalidad.</p>
      <p>
        <a class="btn primary" href="https://app.powerbi.com/view?r=LINK2" target="_blank">Abrir en Power BI</a>
        <a class="btn" href="/proyectos/atencion.md">Metodología</a>
      </p>
    </div>

    <div class="card">
      <h3>Control de Inventario</h3>
      <p>Power Query + modelado en Power BI. ABC y rotación.</p>
      <p>
        <a class="btn primary" href="https://app.powerbi.com/view?r=LINK3" target="_blank">Abrir en Power BI</a>
        <a class="btn" href="/proyectos/inventario.md">Notas técnicas</a>
      </p>
    </div>

  </div>
</div>

<div class="section">
  <h2>🛠️ Tech stack</h2>
  <ul>
    <li>Power BI (DAX con medidas, no columnas)</li>
    <li>Excel/Power Query (ETL, validaciones)</li>
    <li>SQL (JOINs, agregaciones)</li>
    <li>Python (en aprendizaje)</li>
  </ul>
</div>

<footer>
  © {{ site.time | date: '%Y' }} Edin Itzep — Hecho con GitHub Pages
</footer>

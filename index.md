---
title: Portafolio de Edin
layout: default
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css?v=4' | relative_url }}">

<div class="hero">
  <h1>👋 Hola, soy Edin</h1>
  <p>Portafolio de proyectos en <b>Power BI</b>, <b>Excel</b>, <b>SQL</b> y más.</p>
</div>

<div class="section">
  <h2>📊 Proyectos destacados</h2>

  <div class="grid">

    <div class="card">
      <h3>Grocery Shop – Dashboard de Ventas</h3>
      <p>Análisis de ventas por sucursal, crecimiento anual y productos más vendidos.</p>
      <iframe 
        title="GroceryShop"
        width="100%" height="500"
        src="https://app.powerbi.com/view?r=eyJrIjoiN2U3YzYxNzItNmE4Ny00NTM0LTg5ZmEtOWJlMmYwMzdkMzhkIiwidCI6IjVmNTNiNGNlLTYzZDQtNGVlOC04OGQyLTIyZjBiMmQ0YjI3YSIsImMiOjR9"
        frameborder="0" allowfullscreen="true">
      </iframe>
    </div>

    <div class="card">
      <h3>Dashboard de Ventas Generales</h3>
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

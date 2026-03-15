<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
  <meta name="theme-color" content="#ffffff" />
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="mobile-web-app-capable" content="yes" />
  <title>RyCstore - Calculadora 3D</title>
  <link rel="manifest" href="manifest.json" />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: #f5f5f5;
      color: #111;
      padding: 1rem;
    }
    .wrap { max-width: 600px; margin: 0 auto; }

    /* HEADER */
    .header {
      display: flex;
      align-items: center;
      gap: 12px;
      padding: 0.75rem 1.25rem;
      background: #fff;
      border: 1px solid #e0e0e0;
      border-radius: 12px;
      margin-bottom: 12px;
    }
    .header img { width: 48px; height: 48px; object-fit: contain; border-radius: 6px; }
    .header-text h1 { font-size: 16px; font-weight: 600; color: #111; margin: 0; }
    .header-text a { font-size: 12px; color: #1a73e8; text-decoration: none; }
    .header-text a:hover { text-decoration: underline; }

    /* CARDS */
    .card {
      background: #fff;
      border: 1px solid #e0e0e0;
      border-radius: 12px;
      padding: 1rem 1.25rem;
      margin-bottom: 10px;
    }
    .card-title {
      font-size: 11px;
      font-weight: 600;
      color: #888;
      text-transform: uppercase;
      letter-spacing: .06em;
      margin-bottom: 12px;
    }
    .row { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; margin-bottom: 8px; }
    .row.three { grid-template-columns: 1fr 1fr 1fr; }
    .field label { font-size: 12px; color: #666; display: block; margin-bottom: 4px; }
    .field input {
      width: 100%;
      padding: 8px 10px;
      font-size: 14px;
      border: 1px solid #ccc;
      border-radius: 8px;
      background: #fff;
      color: #111;
      outline: none;
    }
    .field input:focus { border-color: #1a73e8; }
    .field .unit { font-size: 11px; color: #aaa; margin-top: 2px; }

    /* BUTTON */
    .btn-calc {
      width: 100%;
      padding: 12px;
      font-size: 15px;
      font-weight: 600;
      border: none;
      border-radius: 10px;
      background: #111;
      color: #fff;
      cursor: pointer;
      margin-bottom: 10px;
      transition: background 0.2s;
    }
    .btn-calc:hover { background: #333; }

    /* RESULTS */
    .result-block {
      background: #f9f9f9;
      border-radius: 8px;
      padding: 12px 14px;
      margin-bottom: 8px;
    }
    .result-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 4px 0;
    }
    .result-row span:first-child { font-size: 13px; color: #666; }
    .result-row span:last-child { font-size: 14px; font-weight: 600; color: #111; }
    .result-row.big span:first-child { font-size: 14px; font-weight: 600; color: #111; }
    .result-row.big span:last-child { font-size: 20px; font-weight: 700; }
    .result-row.highlight span:last-child { color: #1D9E75; }
    .result-row.accent span:last-child { color: #1a73e8; }
    .result-row.warn span:last-child { color: #BA7517; }
    .divider { border: none; border-top: 1px solid #e0e0e0; margin: 12px 0; }
  </style>
</head>
<body>
<div class="wrap">

  <!-- ENCABEZADO -->
  <div class="header">
    <img src="RyCstore_Logo_Sin_Fondo_Limpio.ico" alt="RyC Store Logo" onerror="this.style.display='none'" />
    <div class="header-text">
      <h1>RyCstore — Calculadora de impresión 3D</h1>
      <a href="https://rycstoremendoza.mitiendanube.com" target="_blank">rycstoremendoza.mitiendanube.com</a>
    </div>
  </div>

  <!-- FILAMENTO -->
  <div class="card">
    <div class="card-title">Filamento</div>
    <div class="row">
      <div class="field">
        <label>Precio filamento ($/kg)</label>
        <input type="number" id="precio_kilo" value="8000" min="0" step="100">
        <div class="unit">por kilogramo</div>
      </div>
      <div class="field">
        <label>Peso de la pieza (g)</label>
        <input type="number" id="peso_pieza" value="100" min="0" step="1">
        <div class="unit">gramos</div>
      </div>
    </div>
  </div>

  <!-- TIEMPO -->
  <div class="card">
    <div class="card-title">Tiempo de impresión</div>
    <div class="row">
      <div class="field">
        <label>Horas</label>
        <input type="number" id="horas" value="2" min="0" step="1">
      </div>
      <div class="field">
        <label>Minutos</label>
        <input type="number" id="minutos" value="30" min="0" max="59" step="1">
      </div>
    </div>
  </div>

  <!-- COSTOS POR HORA -->
  <div class="card">
    <div class="card-title">Costos por hora</div>
    <div class="row">
      <div class="field">
        <label>Gasto de luz ($/h)</label>
        <input type="number" id="luz" value="120" min="0" step="10">
      </div>
      <div class="field">
        <label>Desgaste máquina ($/h)</label>
        <input type="number" id="maquina" value="60" min="0" step="10">
      </div>
    </div>
  </div>

  <!-- INSUMOS -->
  <div class="card">
    <div class="card-title">Insumos fijos</div>
    <div class="row three">
      <div class="field">
        <label>Pegamento ($)</label>
        <input type="number" id="pegamento" value="200" min="0" step="10">
      </div>
      <div class="field">
        <label>Insumos ($)</label>
        <input type="number" id="insumos" value="0" min="0" step="10">
      </div>
      <div class="field">
        <label>Otros ($)</label>
        <input type="number" id="otros" value="0" min="0" step="10">
      </div>
    </div>
  </div>

  <!-- MÁRGENES -->
  <div class="card">
    <div class="card-title">Márgenes</div>
    <div class="row">
      <div class="field">
        <label>Margen de error (%)</label>
        <input type="number" id="error" value="20" min="0" max="100" step="1">
        <div class="unit">sobre costo base</div>
      </div>
      <div class="field">
        <label>Margen sobre venta (%)</label>
        <input type="number" id="venta" value="30" min="0" max="100" step="1">
        <div class="unit">sobre precio final</div>
      </div>
    </div>
  </div>

  <button class="btn-calc" onclick="calcular()">Calcular precio →</button>

  <!-- RESULTADOS -->
  <div class="card" id="resultados" style="display:none">
    <div class="card-title">Desglose de costos</div>
    <div class="result-block">
      <div class="result-row"><span>Filamento</span><span id="r_filamento">$0</span></div>
      <div class="result-row"><span>Luz eléctrica</span><span id="r_luz">$0</span></div>
      <div class="result-row"><span>Desgaste máquina</span><span id="r_maquina">$0</span></div>
      <div class="result-row"><span>Pegamento + insumos + otros</span><span id="r_fijos">$0</span></div>
    </div>

    <div class="result-block">
      <div class="result-row"><span>Subtotal costo base</span><span id="r_base">$0</span></div>
      <div class="result-row warn"><span>+ Margen de error</span><span id="r_error">$0</span></div>
      <div class="result-row big"><span>Costo total neto</span><span id="r_neto">$0</span></div>
    </div>

    <hr class="divider">
    <div class="card-title" style="margin-bottom:10px">Distribución del neto</div>
    <div class="row" style="margin-bottom:8px">
      <div class="field">
        <label>Margen sueldo (%)</label>
        <input type="number" id="sueldo_pct" value="40" min="0" max="100" step="1" oninput="distribuir()">
      </div>
      <div class="field">
        <label>Margen empresa (%)</label>
        <input type="number" id="empresa_pct" value="60" min="0" max="100" step="1" oninput="distribuir()">
      </div>
    </div>
    <div class="result-block">
      <div class="result-row accent"><span>Sueldo / mano de obra</span><span id="r_sueldo">$0</span></div>
      <div class="result-row highlight"><span>Ganancia empresa</span><span id="r_empresa">$0</span></div>
    </div>

    <hr class="divider">
    <div class="card-title" style="margin-bottom:10px">Precio de venta final</div>
    <div class="result-block">
      <div class="result-row"><span>Margen sobre venta aplicado</span><span id="r_margen_venta">$0</span></div>
      <div class="result-row big highlight"><span>Precio de venta</span><span id="r_venta">$0</span></div>
    </div>
  </div>

</div>

<script>
  let netoGlobal = 0;

  function fmt(n) {
    return '$' + Math.round(n).toLocaleString('es-AR');
  }

  function calcular() {
    const precio_kilo = parseFloat(document.getElementById('precio_kilo').value) || 0;
    const peso        = parseFloat(document.getElementById('peso_pieza').value) || 0;
    const horas       = parseFloat(document.getElementById('horas').value) || 0;
    const minutos     = parseFloat(document.getElementById('minutos').value) || 0;
    const luz         = parseFloat(document.getElementById('luz').value) || 0;
    const maquina     = parseFloat(document.getElementById('maquina').value) || 0;
    const pegamento   = parseFloat(document.getElementById('pegamento').value) || 0;
    const insumos     = parseFloat(document.getElementById('insumos').value) || 0;
    const otros       = parseFloat(document.getElementById('otros').value) || 0;
    const error_pct   = parseFloat(document.getElementById('error').value) || 0;
    const venta_pct   = parseFloat(document.getElementById('venta').value) || 0;

    const tiempo_h        = horas + minutos / 60;
    const costo_filamento = (precio_kilo / 1000) * peso;
    const costo_luz       = luz * tiempo_h;
    const costo_maquina   = maquina * tiempo_h;
    const costo_fijos     = pegamento + insumos + otros;
    const base            = costo_filamento + costo_luz + costo_maquina + costo_fijos;
    const costo_error     = base * (error_pct / 100);
    const neto            = base + costo_error;
    netoGlobal            = neto;

    document.getElementById('r_filamento').textContent = fmt(costo_filamento);
    document.getElementById('r_luz').textContent       = fmt(costo_luz);
    document.getElementById('r_maquina').textContent   = fmt(costo_maquina);
    document.getElementById('r_fijos').textContent     = fmt(costo_fijos);
    document.getElementById('r_base').textContent      = fmt(base);
    document.getElementById('r_error').textContent     = fmt(costo_error);
    document.getElementById('r_neto').textContent      = fmt(neto);

    const precio_venta      = venta_pct < 100 ? neto / (1 - venta_pct / 100) : neto;
    const margen_venta_monto = precio_venta - neto;
    document.getElementById('r_margen_venta').textContent = fmt(margen_venta_monto);
    document.getElementById('r_venta').textContent        = fmt(precio_venta);

    document.getElementById('resultados').style.display = 'block';
    distribuir();
  }

  function distribuir() {
    if (netoGlobal === 0) return;
    const s     = parseFloat(document.getElementById('sueldo_pct').value) || 0;
    const e     = parseFloat(document.getElementById('empresa_pct').value) || 0;
    const total = s + e;
    const sueldo  = total > 0 ? netoGlobal * (s / total) : 0;
    const empresa = total > 0 ? netoGlobal * (e / total) : 0;
    document.getElementById('r_sueldo').textContent  = fmt(sueldo);
    document.getElementById('r_empresa').textContent = fmt(empresa);
  }
</script>
</body>
</html>

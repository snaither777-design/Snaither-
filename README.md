<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <title>Hub</title>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <style>
    body {
      font-family: 'Helvetica', sans-serif;
      padding: 28px;
      background: #f5f7fb;
    }
    .card {
      background: white;
      padding: 18px;
      border-radius: 10px;
      box-shadow: 0 8px 30px rgba(10,20,30,0.06);
      width: 420px;
      margin: auto;
      text-align: center;
    }
    button {
      margin: 8px;
      padding: 10px 14px;
      border-radius: 8px;
      border: none;
      cursor: pointer;
    }
    .primary { background: #2563eb; color: white; }
    .muted { background: #6b7280; color: white; }
    .success { background: #10b981; color: white; }
    .danger { background: #ef4444; color: white; }
    #output {
      margin-top: 12px;
      color: #374151;
      min-height: 48px;
      word-break: break-word;
    }
    input[type="password"] {
      padding: 8px;
      width: 90%;
      margin-top: 8px;
      border-radius: 6px;
      border: 1px solid #d1d5db;
    }
    small { color: #6b7280; }
    code {
      background: #f3f4f6;
      padding: 2px 6px;
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <div class="card">
    <h2>HUB</h2>
    <button class="primary" id="btnEntrar">Entrar</button>
    <button class="muted" id="btnKey">Conseguir key</button>
    <button class="danger" id="btnAbrir">Abrir</button>

    <div id="output"><small>Pulsa "Conseguir key" para descargar y copiar la página remota.</small></div>
  </div>

  <script>
    const TARGET_URL = "https://scriptsnaizz.blogspot.com/2025/10/script-key-aqui

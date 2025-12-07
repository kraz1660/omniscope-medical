:root{--accent:#0b6;--bg:#f7f7f9;--text:#111}
*{box-sizing:border-box}
body{font-family:Inter,system-ui,Arial,sans-serif;margin:0;color:var(--text);background:var(--bg);-webkit-font-smoothing:antialiased}
.wrap{max-width:1100px;margin:0 auto;padding:28px}
.site-header{background:#fff;border-bottom:1px solid #e6e6e9}
.site-header .wrap{display:flex;align-items:center;justify-content:space-between}
.brand{font-weight:700;text-decoration:none;color:inherit}
.nav a{margin-left:18px;text-decoration:none;color:inherit}
.cta{padding:8px 12px;border-radius:6px;background:var(--accent);color:#002}
.hero{padding:48px 0;background:linear-gradient(90deg,#ffffff 50%, #f0fff4 0)}
.hero-inner{display:flex;gap:24px;align-items:center}
.hero h1{margin:0 0 12px;font-size:28px}
.hero-card{background:#fff;padding:18px;border-radius:10px;box-shadow:0 6px 18px rgba(0,0,0,.06);min-width:240px}
.btn{display:inline-block;padding:10px 14px;border-radius:8px;background:#002;color:#fff;text-decoration:none;margin-right:8px}
.btn.ghost{background:transparent;color:var(--accent);border:1px solid #ddd}
.section{padding:36px 0;background:transparent}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px}
.card{background:#fff;padding:18px;border-radius:10px;box-shadow:0 6px 18px rgba(0,0,0,.04)}
.price{font-weight:700;margin-top:10px}
.steps{list-style:none;padding:0;display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px}
.contact form{display:grid;gap:10px;max-width:600px}
label{display:block;font-size:14px}
input,textarea{width:100%;padding:10px;border-radius:6px;border:1px solid #ddd}
.site-footer{background:#fff;border-top:1px solid #e6e6e9;margin-top:30px;padding:18px}
@media(max-width:800px){.hero-inner{flex-direction:column}}

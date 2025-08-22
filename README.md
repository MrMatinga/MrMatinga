<!-- Fundo animado com partículas -->
<div style="background: radial-gradient(circle at top left, #0f0f1a, #1a0f2f); color:#e0e0e0; padding:40px; font-family: 'Poppins', sans-serif;">

  <!-- Banner com efeito de digitação (uiverse.io) -->
  <div style="text-align:center; margin-bottom:40px;">
    <h1 class="typing-text" style="font-size:64px; background: linear-gradient(90deg,#7c3aed,#b084ff); -webkit-background-clip: text; color: transparent;">
      ✨ MATT ⚡
    </h1>
    <p style="font-size:20px; color:#b0b0c0;">
      CEO da <a href="https://delta-bots-pit.webnode.page" style="color:#7c3aed; text-decoration:none;">Delta Bots</a> • Front-end Developer • 16 anos
    </p>
  </div>

  <!-- Skills com efeito hover glow (uiverse.io) -->
  <div style="display:flex; justify-content:center; gap:25px; flex-wrap:wrap; margin-bottom:40px;">
    <div class="icon-card"><img src="https://skillicons.dev/icons?i=html" width="70"></div>
    <div class="icon-card"><img src="https://skillicons.dev/icons?i=css" width="70"></div>
    <div class="icon-card"><img src="https://skillicons.dev/icons?i=js" width="70"></div>
    <div class="icon-card"><img src="https://skillicons.dev/icons?i=react" width="70"></div>
  </div>

  <!-- Cards 3D com efeito tilt (uiverse.io) -->
  <div style="display:flex; justify-content:center; flex-wrap:wrap; gap:30px; margin-bottom:50px;">
    <div class="tilt-card purple"><h3>Design é identidade</h3><p>Cada detalhe importa</p></div>
    <div class="tilt-card violet"><h3>UI ≠ só pixels</h3><p>Experiências vividas</p></div>
    <div class="tilt-card pink"><h3>Código limpo & acessível</h3><p>Escalabilidade real</p></div>
  </div>

  <!-- Sobre mim com efeito glassmorphism -->
  <div style="display:flex; justify-content:center; flex-wrap:wrap; gap:25px; margin-bottom:40px;">
    <div class="glass-card">Nome: Mateus</div>
    <div class="glass-card">Apelido: MATT ⚡</div>
    <div class="glass-card">Idade: 16 anos</div>
    <div class="glass-card">CEO: <a href="https://delta-bots-pit.webnode.page" style="color:#b084ff; text-decoration:none;">Delta Bots</a></div>
  </div>

  <!-- Botões de contato animados -->
  <div style="text-align:center; margin-top:40px;">
    <a class="btn-neon" href="mailto:mh24092008@gmail.com">📧 Email</a>
    <a class="btn-neon" href="https://github.com/mateusdeltabots/">💻 GitHub</a>
  </div>

  <!-- Frase final -->
  <p style="text-align:center; font-size:20px; margin-top:50px; color:#b0b0c0;">"Eu não apenas programo telas, eu crio <b>experiências digitais memoráveis</b>."</p>
</div>

<!-- Estilos inspirados no uiverse.io -->
<style>
.typing-text {
  overflow: hidden;
  border-right: .15em solid #b084ff;
  white-space: nowrap;
  animation: typing 3.5s steps(30, end), blink-caret .75s step-end infinite;
}
@keyframes typing { from { width: 0 } to { width: 100% } }
@keyframes blink-caret { from, to { border-color: transparent } 50% { border-color: #b084ff; } }

.icon-card {
  padding: 15px;
  border-radius: 15px;
  background: rgba(255,255,255,0.05);
  transition: transform 0.3s, box-shadow 0.3s;
}
.icon-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 15px #b084ff;
}

.tilt-card {
  width: 280px;
  padding: 25px;
  border-radius: 20px;
  color: white;
  text-align: center;
  box-shadow: 0 20px 40px rgba(0,0,0,0.6);
  transition: transform 0.3s;
}
.tilt-card:hover { transform: rotateY(10deg) rotateX(5deg) scale(1.05); }
.purple { background: linear-gradient(135deg,#7c3aed,#b084ff); }
.violet { background: linear-gradient(135deg,#6b21a8,#a78bfa); }
.pink { background: linear-gradient(135deg,#9333ea,#c084fc); }

.glass-card {
  background: rgba(255,255,255,0.05);
  backdrop-filter: blur(10px);
  padding: 20px;
  width: 220px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 15px 35px rgba(0,0,0,0.6);
}

.btn-neon {
  display: inline-block;
  padding: 12px 25px;
  margin: 10px;
  color: white;
  text-decoration: none;
  border: 2px solid #b084ff;
  border-radius: 30px;
  transition: 0.3s;
}
.btn-neon:hover {
  background: #b084ff;
  box-shadow: 0 0 15px #b084ff, 0 0 30px #7c3aed;
}
</style>

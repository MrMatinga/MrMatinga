<div style="background:#ffffff; color:#0a1f44; padding:60px 40px; font-family:'Poppins', sans-serif; line-height:1.6;">

  <!-- Cabeçalho com efeito parallax -->
  <header style="text-align:center; margin-bottom:60px; perspective:1000px;">
    <h1 id="title" style="font-size:72px; font-weight:900; margin:0; color:#0a1f44; letter-spacing:-1px; transition: transform 0.2s;">
      ⛈ MATT ⚡
    </h1>
    <p style="font-size:22px; color:#0a1f44cc; margin-top:10px;">
      CEO da <a href="https://delta-bots-pit.webnode.page" style="color:#00bcd4; text-decoration:none; font-weight:600;">Delta Bots</a> • Front-end Developer • 16 anos
    </p>
  </header>

  <!-- Skills com efeito hover -->
  <section style="display:flex; justify-content:center; gap:40px; flex-wrap:wrap; margin-bottom:60px;">
    <div class="icon"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="64"></div>
    <div class="icon"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="64"></div>
    <div class="icon"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="64"></div>
    <div class="icon"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="64"></div>
  </section>

  <!-- Filosofia com efeito tilt -->
  <section style="display:grid; grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); gap:30px; margin-bottom:60px;">
    <div class="tilt-card"><h3>Design é identidade</h3><p>Cada detalhe importa</p></div>
    <div class="tilt-card"><h3>UI ≠ só pixels</h3><p>Experiências vividas</p></div>
    <div class="tilt-card"><h3>Código limpo & acessível</h3><p>Escalabilidade real</p></div>
  </section>

  <!-- Sobre mim -->
  <section style="display:flex; justify-content:center; flex-wrap:wrap; gap:20px; margin-bottom:60px;">
    <div class="info-card">Nome: Mateus</div>
    <div class="info-card">Apelido: MATT ⚡</div>
    <div class="info-card">Idade: 16 anos</div>
    <div class="info-card">CEO: <a href="https://delta-bots-pit.webnode.page" style="color:#00bcd4; text-decoration:none;">Delta Bots</a></div>
  </section>

  <!-- Contato -->
  <section style="text-align:center; margin-bottom:40px;">
    <a class="btn-follow" href="mailto:mh24092008@gmail.com">📧 Email</a>
    <a class="btn-follow" href="https://github.com/mateusdeltabots/">💻 GitHub</a>
  </section>

  <!-- Frase final -->
  <footer>
    <p style="text-align:center; font-size:18px; color:#0a1f44cc; font-style:italic;">
      "Eu não apenas programo telas, eu crio <b>experiências digitais memoráveis</b>."
    </p>
  </footer>
</div>

<style>
.icon img {
  transition: transform 0.3s, filter 0.3s;
}
.icon:hover img {
  transform: scale(1.2);
  filter: drop-shadow(0 0 8px #00bcd4);
}

.tilt-card {
  background:#f0fbfd;
  border-top:5px solid #00bcd4;
  padding:25px;
  border-radius:10px;
  box-shadow:0 4px 12px rgba(0,0,0,0.05);
  transition: transform 0.2s;
}
.tilt-card:hover {
  transform: rotateY(8deg) rotateX(4deg) scale(1.03);
}

.info-card {
  background:#f8fbff;
  padding:15px 25px;
  border-radius:8px;
  border:1px solid #dce7f3;
  transition: transform 0.3s, box-shadow 0.3s;
}
.info-card:hover {
  transform: translateY(-5px);
  box-shadow:0 6px 15px rgba(0,0,0,0.08);
}

.btn-follow {
  display:inline-block;
  padding:12px 28px;
  margin:5px;
  border:2px solid #00bcd4;
  border-radius:30px;
  color:#0a1f44;
  text-decoration:none;
  font-weight:600;
  position:relative;
  transition: transform 0.2s, background 0.3s;
}
.btn-follow:hover {
  background:#00bcd4;
  color:white;
  transform: translateY(-3px);
}
</style>

<script>
// Efeito parallax no título
document.addEventListener('mousemove', e => {
  const title = document.getElementById('title');
  const x = (window.innerWidth / 2 - e.pageX) / 40;
  const y = (window.innerHeight / 2 - e.pageY) / 40;
  title.style.transform = `rotateY(${x}deg) rotateX(${y}deg)`;
});
</script>

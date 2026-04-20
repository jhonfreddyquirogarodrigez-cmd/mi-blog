<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Narrativa Digital vs. Tradicional</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --text-primary: #1a1a1a; --text-secondary: #555; --text-muted: #999;
    --bg: #fafaf8; --surface: #fff; --border: #e8e6e0;
    --blue: #378ADD; --blue-light: #E6F1FB; --blue-dark: #185FA5;
    --teal: #1D9E75; --teal-light: #E1F5EE; --teal-dark: #0F6E56;
  }
  body { font-family: 'DM Sans', sans-serif; background: var(--bg); color: var(--text-primary); }
  .container { max-width: 780px; margin: 0 auto; padding: 0 2rem; }

  header { background: var(--surface); border-bottom: 0.5px solid var(--border); padding: 1rem 0; position: sticky; top: 0; z-index: 100; }
  .header-inner { display: flex; justify-content: space-between; align-items: center; max-width: 780px; margin: 0 auto; padding: 0 2rem; }
  .site-name { font-family: 'Playfair Display', serif; font-size: 1rem; font-weight: 600; }
  .site-tag { font-size: 11px; color: var(--text-muted); letter-spacing: 0.08em; text-transform: uppercase; }

  .hero { padding: 4rem 0 3rem; border-bottom: 0.5px solid var(--border); }
  .hero-label { font-size: 11px; text-transform: uppercase; letter-spacing: 0.12em; color: var(--text-muted); display: flex; align-items: center; gap: 10px; margin-bottom: 1.5rem; }
  .hero-label::before { content: ''; display: inline-block; width: 28px; height: 1px; background: var(--text-muted); }
  .hero h1 { font-family: 'Playfair Display', serif; font-size: 2.8rem; font-weight: 600; line-height: 1.15; margin-bottom: 1.2rem; }
  .hero h1 em { font-style: italic; color: var(--text-secondary); }
  .hero-desc { font-size: 15px; color: var(--text-secondary); line-height: 1.75; max-width: 560px; margin-bottom: 2rem; }
  .hero-meta { display: flex; gap: 1.5rem; font-size: 12px; color: var(--text-muted); }

  .tabs { display: flex; border-bottom: 0.5px solid var(--border); background: var(--surface); position: sticky; top: 57px; z-index: 90; overflow-x: auto; }
  .tab-btn { background: none; border: none; border-bottom: 2px solid transparent; padding: 1rem 1.2rem; font-size: 13px; font-family: 'DM Sans', sans-serif; font-weight: 400; color: var(--text-secondary); cursor: pointer; white-space: nowrap; transition: all 0.2s; margin-bottom: -0.5px; }
  .tab-btn:hover { color: var(--text-primary); }
  .tab-btn.active { color: var(--text-primary); font-weight: 500; border-bottom-color: var(--text-primary); }

  .content { padding: 3rem 0; }
  .section { display: none; }
  .section.active { display: block; }
  .section-title { font-family: 'Playfair Display', serif; font-size: 1.5rem; font-weight: 600; margin-bottom: 0.5rem; }
  .section-intro { font-size: 14px; color: var(--text-secondary); margin-bottom: 2rem; line-height: 1.65; }

  .compare-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1px; background: var(--border); border-radius: 12px; overflow: hidden; margin-bottom: 2rem; }
  .compare-col { background: var(--surface); padding: 2rem; }
  .compare-col h3 { font-family: 'Playfair Display', serif; font-size: 1.1rem; font-weight: 600; margin-bottom: 0.3rem; }
  .col-sub { font-size: 11px; color: var(--text-muted); letter-spacing: 0.06em; margin-bottom: 1.4rem; padding-bottom: 1rem; border-bottom: 0.5px solid var(--border); }
  .compare-col.digital { border-top: 3px solid var(--blue); }
  .compare-col.trad { border-top: 3px solid var(--teal); }
  .trait { display: flex; gap: 10px; margin-bottom: 1rem; align-items: flex-start; }
  .trait-dot { width: 5px; height: 5px; border-radius: 50%; margin-top: 8px; flex-shrink: 0; }
  .digital .trait-dot { background: var(--blue); }
  .trad .trait-dot { background: var(--teal); }
  .trait-text strong { display: block; font-size: 13px; font-weight: 500; margin-bottom: 2px; }
  .trait-text span { font-size: 13px; color: var(--text-secondary); line-height: 1.55; }

  .source-box { border: 0.5px solid var(--border); border-radius: 10px; padding: 1.4rem 1.6rem; margin-bottom: 1.5rem; background: var(--surface); }
  .source-label { font-size: 10px; text-transform: uppercase; letter-spacing: 0.12em; color: var(--text-muted); margin-bottom: 0.8rem; }
  .source-box p { font-size: 13.5px; line-height: 1.75; color: var(--text-primary); margin-bottom: 0.7rem; }
  .source-box p:last-child { margin-bottom: 0; }
  .source-cite { font-size: 11px; color: var(--text-muted); font-style: italic; margin-top: 0.8rem; padding-top: 0.6rem; border-top: 0.5px solid var(--border); }

  .debate-q { font-family: 'Playfair Display', serif; font-size: 1.3rem; font-style: italic; line-height: 1.45; padding-left: 1.2rem; border-left: 2px solid var(--border); margin-bottom: 2rem; color: var(--text-secondary); }
  .vote-box { background: var(--surface); border: 0.5px solid var(--border); border-radius: 12px; padding: 1.8rem; margin-bottom: 2rem; }
  .vote-labels { display: flex; justify-content: space-between; font-size: 12px; color: var(--text-secondary); margin-bottom: 0.7rem; }
  .bar-bg { height: 6px; background: #eee; border-radius: 99px; overflow: hidden; margin-bottom: 1.5rem; }
  .bar-fill { height: 100%; border-radius: 99px; background: linear-gradient(90deg, var(--blue), var(--teal)); transition: width 0.6s cubic-bezier(0.4,0,0.2,1); width: 50%; }
  .vote-btns { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .v-btn { padding: 0.75rem 1rem; border: 0.5px solid var(--border); background: var(--bg); border-radius: 8px; font-size: 13px; font-family: 'DM Sans', sans-serif; cursor: pointer; transition: all 0.18s; color: var(--text-primary); }
  .v-btn:hover { background: #f0f0ec; }
  .v-btn.sel-a { border-color: var(--blue); background: var(--blue-light); color: var(--blue-dark); }
  .v-btn.sel-b { border-color: var(--teal); background: var(--teal-light); color: var(--teal-dark); }
  .v-result { text-align: center; font-size: 13px; color: var(--text-muted); margin-top: 1rem; min-height: 18px; }

  .arg-item { border: 0.5px solid var(--border); border-radius: 10px; margin-bottom: 10px; overflow: hidden; background: var(--surface); }
  .arg-header { display: flex; justify-content: space-between; align-items: center; padding: 1rem 1.3rem; cursor: pointer; gap: 1rem; }
  .arg-header:hover { background: var(--bg); }
  .arg-title { font-size: 13px; font-weight: 500; flex: 1; }
  .arg-right { display: flex; align-items: center; gap: 10px; }
  .arg-tag { font-size: 11px; padding: 3px 10px; border-radius: 99px; white-space: nowrap; }
  .tag-d { background: var(--blue-light); color: var(--blue-dark); }
  .tag-t { background: var(--teal-light); color: var(--teal-dark); }
  .arg-icon { font-size: 18px; color: var(--text-muted); transition: transform 0.2s; line-height: 1; }
  .arg-item.open .arg-icon { transform: rotate(45deg); }
  .arg-body { display: none; padding: 0 1.3rem 1.2rem; font-size: 13px; color: var(--text-secondary); line-height: 1.7; border-top: 0.5px solid var(--border); padding-top: 1rem; }
  .arg-item.open .arg-body { display: block; }
  .arg-source { font-size: 11px; color: var(--text-muted); font-style: italic; margin-top: 0.6rem; }

  .refl-box { background: var(--surface); border: 0.5px solid var(--border); border-radius: 12px; padding: 2rem; margin-bottom: 2rem; }
  .refl-box p { font-size: 15px; line-height: 1.8; margin-bottom: 1rem; }
  .refl-box p:last-child { margin-bottom: 0; }
  .refl-box em { font-family: 'Playfair Display', serif; font-style: italic; }

  .ref-list { margin-top: 2rem; padding-top: 1.5rem; border-top: 0.5px solid var(--border); }
  .ref-label { font-size: 11px; text-transform: uppercase; letter-spacing: 0.1em; color: var(--text-muted); margin-bottom: 1rem; }
  .ref-item { font-size: 12px; color: var(--text-secondary); line-height: 1.65; margin-bottom: 0.7rem; padding-left: 1.2rem; text-indent: -1.2rem; }

  @media (max-width: 600px) {
    .hero h1 { font-size: 2rem; }
    .compare-grid { grid-template-columns: 1fr; }
    .vote-btns { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<header>
  <div class="header-inner">
    <span class="site-name">Comunicación y Narrativa</span>
    <span class="site-tag">Jhon quiroga · Uniminuto</span>
  </div>
</header>

<div class="container">
  <div class="hero">
    <div class="hero-label">Análisis comparativo · Comunicación digital</div>
    <h1>Narrativa digital<br><em>vs.</em> narrativa tradicional</h1>
    <p class="hero-desc">¿Cambia el medio el mensaje? Un análisis sobre cómo cada formato construye argumentos, conecta con el lector y redefine el acto de narrar en la era transmedia.</p>
    <div class="hero-meta">
      <span>Lectura 6 min</span><span>·</span>
      <span>Blog interactivo</span><span>·</span>
      <span>Lectura y Escritura en el Contexto Digital · Uniminuto</span>
    </div>
  </div>
</div>

<div class="tabs">
  <div class="container" style="padding:0;max-width:780px;display:flex;overflow-x:auto">
    <button class="tab-btn active" onclick="showTab('comparacion',this)">Comparación</button>
    <button class="tab-btn" onclick="showTab('fuentes',this)">Voces académicas</button>
    <button class="tab-btn" onclick="showTab('debate',this)">¿Cuál argumenta mejor?</button>
    <button class="tab-btn" onclick="showTab('argumentos',this)">Argumentos clave</button>
    <button class="tab-btn" onclick="showTab('conclusion',this)">Conclusión</button>
  </div>
</div>

<div class="container">
<div class="content">

  <div id="comparacion" class="section active">
    <p class="section-title">Dos formas de narrar el mundo</p>
    <p class="section-intro">Desde las pinturas rupestres hasta las redes sociales, la humanidad buscó siempre nuevos soportes para sus historias. Karbaum (2021) lo resume con claridad: narrar es existir, y cada civilización ha usado sus medios disponibles para transmitir experiencias, emociones e información. El soporte, sin embargo, no es neutro: transforma radicalmente cómo se construye y se recibe la narrativa.</p>

    <div class="compare-grid">
      <div class="compare-col digital">
        <h3>Narrativa digital</h3>
        <p class="col-sub">Hipertextual · Multimedial · No lineal</p>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Estructura no lineal</strong><span>El lector elige su recorrido mediante hipervínculos y menús. El autor cede parte del control narrativo.</span></div></div>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Multimodalidad</strong><span>Texto, imagen, video, sonido e interactividad convergen en un mismo espacio narrativo simultáneamente.</span></div></div>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Prosumidores activos</strong><span>La irrupción digital genera prosumidores que crean y redistribuyen contenido, convirtiendo al receptor en co-autor (Karbaum, 2021).</span></div></div>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Traslación discursiva</strong><span>Los nuevos medios asimilan fórmulas de los precedentes antes de desarrollar su propio lenguaje —igual que el cine tomó el teatro (Karbaum y Oré, 2020).</span></div></div>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Inmediatez y escala</strong><span>En plataformas como YouTube se suben 500 horas de video cada minuto (Mohsin, 2020, cit. en Karbaum, 2021), una escala narrativa sin precedentes históricos.</span></div></div>
      </div>
      <div class="compare-col trad">
        <h3>Narrativa tradicional</h3>
        <p class="col-sub">Lineal · Monomedial · Secuencial</p>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Estructura lineal</strong><span>El autor controla el ritmo y el orden: inicio, desarrollo y cierre definidos desde la escritura misma.</span></div></div>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Texto y oralidad como eje</strong><span>Desde las pinturas cavernarias, imagen y texto han ido fusionándose. La escritura es, en sí, una evolución de los gráficos ancestrales (Karbaum, 2021).</span></div></div>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Permanencia y autoridad</strong><span>El texto impreso es estable. Esa fijeza crea un contrato de responsabilidad entre autor y lector que refuerza la autoridad del argumento.</span></div></div>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Serialidad y ciclo</strong><span>Sagas como Harry Potter demuestran que la narrativa tradicional puede crear universos que migran hacia lo transmedia sin perder coherencia (Muñoz-Rico, 2022).</span></div></div>
        <div class="trait"><div class="trait-dot"></div><div class="trait-text"><strong>Vínculo emocional duradero</strong><span>La continuidad cronológica y el factor de reconocimiento intensifican la identificación del lector con personajes y mundos ficticios (Muñoz-Rico, 2022).</span></div></div>
      </div>
    </div>

    <div class="ref-list">
      <p class="ref-label">Fuentes</p>
      <p class="ref-item">Karbaum Padilla, G. (2021). <em>La evolución de la narrativa audiovisual: analógica, transmedia y social media.</em> UPC. https://elibro.net/es/ereader/uniminuto/187521</p>
      <p class="ref-item">Paredes Otero, G. (Coord.). (2022). <em>Narrativas y usuarios de la sociedad transmedia</em> (1.ª ed.). Dykinson. https://elibro.net/es/ereader/uniminuto/227572</p>
    </div>
  </div>

  <div id="fuentes" class="section">
    <p class="section-title">Voces académicas</p>
    <p class="section-intro">Los dos recursos de tu trabajo aportan perspectivas complementarias: uno analiza la evolución del soporte narrativo audiovisual; el otro examina cómo las narrativas literarias migran hacia el ecosistema digital transmedia.</p>

    <div class="source-box">
      <p class="source-label">Fuente 1 — Karbaum Padilla (2021) · La evolución de la narrativa audiovisual</p>
      <p>Karbaum propone el modelo de <strong>traslación discursiva audiovisual</strong>: cada nuevo medio no inventa su narrativa desde cero, sino que primero asimila las fórmulas del medio precedente, luego las madura y finalmente genera su propio lenguaje. El cine tomó la puesta en escena teatral; la televisión, los formatos radiofónicos y fílmicos; las redes sociales, los esquemas del periodismo y el entretenimiento televisivo.</p>
      <p>El autor identifica dos tipos de transformaciones narrativas: las <strong>endógenas</strong> (innovaciones propias de la industria audiovisual, como nuevas cámaras o técnicas de edición) y las <strong>exógenas</strong> (factores externos como guerras, pandemias o revoluciones tecnológicas que reconfiguran el contenido). La COVID-19, por ejemplo, paralizó rodajes y generó una narrativa doméstica forzada que cambió tanto la forma como el fondo de las historias.</p>
      <p>Un elemento central de su análisis es el surgimiento de los <strong>prosumidores</strong>: usuarios digitales que no solo consumen sino que producen y redistribuyen contenido audiovisual, generando tensiones con las corporaciones que controlan los derechos de las historias. Quien controla los discursos, sostiene Karbaum, controla la sociedad a nivel político, económico y cultural.</p>
      <p class="source-cite">Karbaum Padilla, G. (2021). La evolución de la narrativa audiovisual: analógica, transmedia y social media. Universidad Peruana de Ciencias Aplicadas (UPC). https://elibro.net/es/ereader/uniminuto/187521?page=18</p>
    </div>

    <div class="source-box">
      <p class="source-label">Fuente 2 — Muñoz-Rico en Paredes Otero (2022) · Narrativas y usuarios de la sociedad transmedia</p>
      <p>Este capítulo analiza sagas literarias como Harry Potter, El Señor de los Anillos, El Diario de Greg y Gerónimo Stilton para demostrar que la narrativa tradicional no desaparece con lo digital: <strong>migra y se amplifica</strong>. Las sagas más exitosas son las que mejor han sabido aprovechar la narrativa transmedia, expandiéndose hacia el cine, la televisión, los videojuegos, las páginas web y las comunidades fandom.</p>
      <p>La autora distingue entre <strong>serie</strong> y <strong>ciclo</strong> narrativo: en la serie, los volúmenes son autónomos; en el ciclo, la cronología y la evolución de personajes son el vínculo que le da coherencia al conjunto. Harry Potter es un ciclo en el que el personaje crece con el lector, lo que genera una identificación emocional especialmente poderosa.</p>
      <p>El caso de Pottermore —la plataforma digital oficial de Harry Potter— ilustra cómo una narrativa tradicional puede reinventarse digitalmente sin perder su identidad: ofreció experiencias interactivas, contenidos exclusivos de Rowling y la posibilidad de acceder a versiones digitales y audiolibros, demostrando que el texto y su dimensión digital se hibridan formando una unidad indisoluble.</p>
      <p class="source-cite">Paredes Otero, G. (Coord.). (2022). Narrativas y usuarios de la sociedad transmedia (1.ª ed.). Dykinson. https://elibro.net/es/ereader/uniminuto/227572?page=240</p>
    </div>
  </div>

  <div id="debate" class="section">
    <p class="section-title">¿Cuál argumenta mejor?</p>
    <p class="debate-q">"¿El formato digital o el tradicional logra argumentar con mayor eficacia comunicativa?"</p>

    <div class="vote-box">
      <div class="vote-labels">
        <span id="lbl-d">Digital — 50%</span>
        <span id="lbl-t">Tradicional — 50%</span>
      </div>
      <div class="bar-bg"><div class="bar-fill" id="bfill"></div></div>
      <p style="font-size:12px;color:var(--text-muted);text-align:center;margin-bottom:1rem">Vota y ve cómo se mueve el debate</p>
      <div class="vote-btns">
        <button class="v-btn" id="vbA" onclick="votar('a')">La narrativa digital</button>
        <button class="v-btn" id="vbB" onclick="votar('b')">La narrativa tradicional</button>
      </div>
      <p class="v-result" id="vres"></p>
    </div>

    <div class="source-box">
      <p class="source-label">A favor de la narrativa digital — desde Karbaum (2021)</p>
      <p>La narrativa digital argumenta con mayor <strong>alcance, velocidad y evidencia multimedial</strong>. Un argumento apoyado en video, datos interactivos e hipertexto verificable tiene más capas de persuasión que el texto plano. Los prosumidores amplifican y debaten los argumentos en tiempo real, generando lo que Jenkins denomina inteligencia colectiva. La escala es incomparable: 500 horas de video subidas a YouTube cada minuto ilustran la potencia argumentativa del ecosistema digital.</p>
      <p>Además, Karbaum documenta que la narrativa digital logra trasladar sus discursos más allá de sus fronteras originales: las plataformas <em>over the top</em> como Netflix o Disney+ han redefinido lo que significa contar una historia y llegar a audiencias globales de forma simultánea.</p>
    </div>

    <div class="source-box">
      <p class="source-label">A favor de la narrativa tradicional — desde Muñoz-Rico (2022)</p>
      <p>La narrativa tradicional argumenta con mayor <strong>profundidad, cohesión y vínculo emocional</strong>. Las sagas literarias analizadas —de Tolkien a Rowling— construyeron universos argumentales complejos que ningún formato fragmentado digital puede sostener con igual coherencia interna. La estructura lineal obliga al autor a un rigor lógico que el texto digital, con su fragmentación e hipertextualidad, no siempre puede garantizar.</p>
      <p>La serialidad y la continuidad cronológica crean un factor de reconocimiento que favorece la asimilación profunda de los argumentos. Ese mismo universo, cuando migra a lo digital, gana alcance pero su fundamento sigue siendo la obra impresa original: sin ella, el ecosistema transmedia no tendría dónde anclarse.</p>
    </div>
  </div>

  <div id="argumentos" class="section">
    <p class="section-title">Argumentos clave del debate</p>
    <p class="section-intro">Cada argumento está fundamentado en las fuentes de tu trabajo. Toca para expandirlo y ver su desarrollo y referencia.</p>
    <div id="arg-list"></div>

    <div class="ref-list">
      <p class="ref-label">Referencias bibliográficas</p>
      <p class="ref-item">Karbaum Padilla, G. (2021). <em>La evolución de la narrativa audiovisual: analógica, transmedia y social media.</em> Universidad Peruana de Ciencias Aplicadas (UPC). https://elibro.net/es/ereader/uniminuto/187521?page=18</p>
      <p class="ref-item">Paredes Otero, G. (Coord.). (2022). <em>Narrativas y usuarios de la sociedad transmedia</em> (1.ª ed.). Dykinson. https://elibro.net/es/ereader/uniminuto/227572?page=240</p>
    </div>
  </div>

  <div id="conclusion" class="section">
    <p class="section-title">Reflexión final</p>
    <div class="refl-box">
      <p>Las dos fuentes consultadas apuntan en la misma dirección: la oposición entre narrativa digital y tradicional es, en buena medida, una falsa dicotomía. Karbaum (2021) demuestra que cada nuevo medio asimila primero las fórmulas del anterior antes de desarrollar su propio lenguaje. Muñoz-Rico (2022) confirma que las narrativas más poderosas de nuestra época son precisamente las que supieron migrar de un formato al otro sin perder su identidad.</p>
      <p>La narrativa tradicional argumenta con mayor <em>profundidad y cohesión</em>; la digital, con mayor <em>alcance y evidencia multimedial</em>. La pregunta pertinente no es cuál supera a la otra, sino qué objetivo comunicativo perseguimos y a qué lector o espectador nos dirigimos.</p>
      <p>En la era transmedia, la narrativa más eficaz no elige un bando: los hibrida. Harry Potter nació como libro, se convirtió en película, se expandió en Pottermore y vive hoy en comunidades fandom globales. Ese trayecto —de lo tradicional a lo digital y vuelta al texto— es la respuesta más elocuente a nuestra pregunta inicial.</p>
    </div>

    <div class="ref-list">
      <p class="ref-label">Referencias bibliográficas</p>
      <p class="ref-item">Karbaum Padilla, G. (2021). <em>La evolución de la narrativa audiovisual: analógica, transmedia y social media.</em> Universidad Peruana de Ciencias Aplicadas (UPC). https://elibro.net/es/ereader/uniminuto/187521?page=18</p>
      <p class="ref-item">Paredes Otero, G. (Coord.). (2022). <em>Narrativas y usuarios de la sociedad transmedia</em> (1.ª ed.). Dykinson. https://elibro.net/es/ereader/uniminuto/227572?page=240</p>
    </div>
  </div>

</div>
</div>

<script>
const args = [
  { tag:'d', label:'La hipertextualidad amplía y verifica el argumento', body:'En la narrativa digital, cada hipervínculo es una cita activa: el lector puede verificar fuentes en tiempo real. Karbaum (2021) señala que los prosumidores en plataformas como YouTube generan y redistribuyen argumentos a una escala sin precedentes, enriqueciendo el debate colectivo de forma que ningún texto impreso puede replicar.', src:'Karbaum Padilla, G. (2021). La evolución de la narrativa audiovisual. UPC.' },
  { tag:'t', label:'La linealidad garantiza coherencia argumentativa profunda', body:'La estructura secuencial obliga al autor a construir un hilo argumental sin interrupciones. Muñoz-Rico (2022) demuestra que sagas como El Señor de los Anillos o Harry Potter construyeron universos argumentales de una cohesión interna que ningún formato fragmentado digital puede sostener con igual rigor lógico.', src:'Paredes Otero, G. (Coord.). (2022). Narrativas y usuarios de la sociedad transmedia. Dykinson.' },
  { tag:'d', label:'La multimedia amplía las capas de persuasión', body:'Karbaum (2021) documenta que plataformas over the top como Netflix o Disney+ y los prosumidores de YouTube han redefinido qué se entiende por argumento audiovisual. La multimodalidad apela a múltiples formas de inteligencia y memoria, ampliando el alcance persuasivo más allá de lo que el texto plano puede conseguir.', src:'Karbaum Padilla, G. (2021). La evolución de la narrativa audiovisual. UPC.' },
  { tag:'t', label:'La permanencia genera autoridad narrativa duradera', body:'Muñoz-Rico (2022) señala que Harry Potter y El Señor de los Anillos mantienen su autoridad narrativa décadas después de su publicación precisamente por la densidad y estabilidad de su texto original. Esa fijeza crea un contrato de responsabilidad entre autor y lector que los formatos efímeros digitales difícilmente pueden replicar.', src:'Paredes Otero, G. (Coord.). (2022). Narrativas y usuarios de la sociedad transmedia. Dykinson.' },
  { tag:'d', label:'El prosumidor transforma el argumento en conversación colectiva', body:'Karbaum (2021) documenta que la tecnología digital genera prosumidores que se apropian de historias y las redistribuyen, originando un ecosistema argumentativo colectivo. La tesis no muere con el texto: vive y evoluciona en la conversación pública continua, lo que potencia su alcance e impacto cultural.', src:'Karbaum Padilla, G. (2021). La evolución de la narrativa audiovisual. UPC.' },
  { tag:'t', label:'La serialidad construye vínculos emocionales duraderos', body:'Muñoz-Rico (2022) argumenta que la lógica de la saga literaria —repetición, continuidad cronológica, personajes que evolucionan— crea un factor de reconocimiento que favorece la asimilación emocional. Cuando esa saga migra al entorno digital, el anclaje emocional lo provee siempre la obra original impresa; sin ella, el ecosistema transmedia no tendría fundamento.', src:'Paredes Otero, G. (Coord.). (2022). Narrativas y usuarios de la sociedad transmedia. Dykinson.' },
];

const list = document.getElementById('arg-list');
args.forEach(a => {
  const div = document.createElement('div');
  div.className = 'arg-item';
  div.innerHTML = `<div class="arg-header" onclick="this.parentElement.classList.toggle('open')"><span class="arg-title">${a.label}</span><div class="arg-right"><span class="arg-tag ${a.tag==='d'?'tag-d':'tag-t'}">${a.tag==='d'?'Digital':'Tradicional'}</span><span class="arg-icon">+</span></div></div><div class="arg-body">${a.body}<p class="arg-source">${a.src}</p></div>`;
  list.appendChild(div);
});

function showTab(id, btn) {
  document.querySelectorAll('.section').forEach(s=>s.classList.remove('active'));
  document.querySelectorAll('.tab-btn').forEach(b=>b.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  btn.classList.add('active');
}

let votos={a:50,b:50}, votado=false;
function votar(tipo) {
  if(votado) return; votado=true;
  votos[tipo]+=15;
  const total=votos.a+votos.b;
  const pa=Math.round(votos.a/total*100), pb=100-pa;
  document.getElementById('bfill').style.width=pa+'%';
  document.getElementById('lbl-d').textContent='Digital — '+pa+'%';
  document.getElementById('lbl-t').textContent='Tradicional — '+pb+'%';
  document.getElementById('vbA').className='v-btn'+(tipo==='a'?' sel-a':'');
  document.getElementById('vbB').className='v-btn'+(tipo==='b'?' sel-b':'');
  document.getElementById('vres').textContent=tipo==='a'?'Votaste por la narrativa digital.':'Votaste por la narrativa tradicional.';
}
</script>
</body>
</html>

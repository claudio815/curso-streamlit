<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Streamlit Academy — Do Zero ao Avançado</title>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Syne:wght@400;600;800&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0e1a;
    --surface: #111827;
    --surface2: #1a2235;
    --border: #1e2d47;
    --accent: #ff4b6e;
    --accent2: #00d4ff;
    --accent3: #7c3aed;
    --green: #10b981;
    --yellow: #f59e0b;
    --text: #e2e8f0;
    --muted: #64748b;
    --code-bg: #0d1117;
  }

  * { margin:0; padding:0; box-sizing:border-box; }

  body {
    font-family: 'Inter', sans-serif;
    background: var(--bg);
    color: var(--text);
    font-size: 15px;
    line-height: 1.7;
  }

  /* ── HERO ── */
  .hero {
    background: linear-gradient(135deg, #0a0e1a 0%, #0f1c3a 50%, #0a0e1a 100%);
    padding: 48px 20px 40px;
    text-align: center;
    position: relative;
    overflow: hidden;
    border-bottom: 1px solid var(--border);
  }
  .hero::before {
    content: '';
    position: absolute;
    top: -60px; left: 50%; transform: translateX(-50%);
    width: 400px; height: 400px;
    background: radial-gradient(circle, rgba(255,75,110,.15) 0%, transparent 70%);
    pointer-events: none;
  }
  .badge {
    display: inline-block;
    background: rgba(255,75,110,.12);
    border: 1px solid rgba(255,75,110,.3);
    color: var(--accent);
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    padding: 4px 12px;
    border-radius: 20px;
    letter-spacing: .08em;
    margin-bottom: 18px;
  }
  .hero h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(28px, 7vw, 52px);
    font-weight: 800;
    line-height: 1.1;
    margin-bottom: 14px;
  }
  .hero h1 span { color: var(--accent); }
  .hero p { color: var(--muted); font-size: 14px; max-width: 500px; margin: 0 auto 28px; }

  .stats {
    display: flex;
    justify-content: center;
    gap: 24px;
    flex-wrap: wrap;
  }
  .stat {
    text-align: center;
  }
  .stat-n {
    font-family: 'Syne', sans-serif;
    font-size: 26px;
    font-weight: 800;
    color: var(--accent2);
  }
  .stat-l { font-size: 11px; color: var(--muted); text-transform: uppercase; letter-spacing: .06em; }

  /* ── NAV TABS ── */
  .nav-tabs {
    display: flex;
    overflow-x: auto;
    gap: 4px;
    padding: 12px 16px;
    background: var(--surface);
    border-bottom: 1px solid var(--border);
    -webkit-overflow-scrolling: touch;
    scrollbar-width: none;
  }
  .nav-tabs::-webkit-scrollbar { display: none; }
  .tab-btn {
    flex-shrink: 0;
    padding: 7px 14px;
    border-radius: 8px;
    border: 1px solid var(--border);
    background: transparent;
    color: var(--muted);
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    cursor: pointer;
    transition: all .2s;
    white-space: nowrap;
  }
  .tab-btn.active {
    background: var(--accent);
    border-color: var(--accent);
    color: white;
  }

  /* ── LESSON PANEL ── */
  .panel { display: none; padding: 20px 16px; }
  .panel.active { display: block; }

  /* ── MODULE CARD ── */
  .module-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 14px;
    margin-bottom: 16px;
    overflow: hidden;
    transition: border-color .2s;
  }
  .module-card:hover { border-color: var(--accent); }

  .module-header {
    display: flex;
    align-items: center;
    gap: 14px;
    padding: 16px 18px;
    cursor: pointer;
  }
  .module-num {
    width: 36px; height: 36px;
    border-radius: 10px;
    background: linear-gradient(135deg, var(--accent), var(--accent3));
    display: flex; align-items: center; justify-content: center;
    font-family: 'Syne', sans-serif;
    font-size: 14px;
    font-weight: 800;
    flex-shrink: 0;
  }
  .module-info { flex: 1 }
  .module-title { font-family: 'Syne', sans-serif; font-weight: 600; font-size: 15px; }
  .module-sub { font-size: 12px; color: var(--muted); }
  .module-arrow {
    font-size: 18px;
    color: var(--muted);
    transition: transform .3s;
  }
  .module-card.open .module-arrow { transform: rotate(90deg); color: var(--accent); }

  .module-body { display: none; padding: 0 18px 18px; }
  .module-card.open .module-body { display: block; }

  /* ── CONTENT BLOCKS ── */
  .section-title {
    font-family: 'Syne', sans-serif;
    font-size: 13px;
    font-weight: 600;
    color: var(--accent2);
    text-transform: uppercase;
    letter-spacing: .08em;
    margin: 18px 0 10px;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .section-title::after {
    content: '';
    flex: 1;
    height: 1px;
    background: var(--border);
  }

  p { margin-bottom: 12px; font-size: 14px; }

  /* ── CODE BLOCK ── */
  .code-block {
    background: var(--code-bg);
    border: 1px solid #1e2d47;
    border-left: 3px solid var(--accent);
    border-radius: 8px;
    margin: 12px 0;
    overflow: hidden;
  }
  .code-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 8px 14px;
    background: #0d1117;
    border-bottom: 1px solid #1e2d47;
  }
  .code-lang {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--accent);
    letter-spacing: .06em;
  }
  .copy-btn {
    font-size: 11px;
    color: var(--muted);
    background: none;
    border: none;
    cursor: pointer;
    font-family: 'JetBrains Mono', monospace;
    padding: 2px 8px;
    border-radius: 4px;
    transition: all .2s;
  }
  .copy-btn:active { background: var(--accent); color: white; }
  pre {
    padding: 14px;
    overflow-x: auto;
    font-family: 'JetBrains Mono', monospace;
    font-size: 13px;
    line-height: 1.6;
    -webkit-overflow-scrolling: touch;
  }
  .kw { color: #ff79c6; }
  .fn { color: #50fa7b; }
  .st { color: #f1fa8c; }
  .cm { color: #6272a4; font-style: italic; }
  .nb { color: #8be9fd; }
  .op { color: #ff79c6; }
  .nm { color: #bd93f9; }

  /* ── CALLOUTS ── */
  .callout {
    border-radius: 10px;
    padding: 14px 16px;
    margin: 14px 0;
    border-left: 4px solid;
    font-size: 13px;
  }
  .callout-tip { background: rgba(16,185,129,.08); border-color: var(--green); }
  .callout-warn { background: rgba(245,158,11,.08); border-color: var(--yellow); }
  .callout-info { background: rgba(0,212,255,.08); border-color: var(--accent2); }
  .callout-hw { background: rgba(124,58,237,.08); border-color: var(--accent3); }
  .callout-icon { font-size: 16px; margin-bottom: 6px; display: block; }

  /* ── EXERCISE CARD ── */
  .exercise-card {
    background: rgba(124,58,237,.06);
    border: 1px solid rgba(124,58,237,.25);
    border-radius: 12px;
    padding: 16px;
    margin: 14px 0;
  }
  .exercise-title {
    font-family: 'Syne', sans-serif;
    font-weight: 600;
    font-size: 14px;
    color: var(--accent3);
    margin-bottom: 8px;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .ex-badge {
    font-size: 10px;
    background: var(--accent3);
    color: white;
    padding: 2px 8px;
    border-radius: 10px;
    font-family: 'JetBrains Mono', monospace;
  }
  .exercise-list { padding-left: 18px; }
  .exercise-list li { font-size: 13px; margin-bottom: 6px; }

  /* ── CONCEPT PILLS ── */
  .pill-row { display: flex; flex-wrap: wrap; gap: 8px; margin: 10px 0; }
  .pill {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    padding: 4px 10px;
    border-radius: 20px;
    background: var(--surface2);
    border: 1px solid var(--border);
    color: var(--accent2);
  }

  /* ── TERMUX NOTE ── */
  .termux-box {
    background: linear-gradient(135deg, rgba(0,212,255,.06), rgba(124,58,237,.06));
    border: 1px solid rgba(0,212,255,.2);
    border-radius: 12px;
    padding: 16px;
    margin: 14px 0;
  }
  .termux-title {
    font-family: 'Syne', sans-serif;
    font-size: 13px;
    font-weight: 600;
    color: var(--accent2);
    margin-bottom: 10px;
    display: flex;
    align-items: center;
    gap: 6px;
  }

  /* ── PROGRESS BAR ── */
  .progress-wrap { margin: 20px 0 10px; }
  .progress-label { font-size: 12px; color: var(--muted); margin-bottom: 6px; display: flex; justify-content: space-between; }
  .progress-bar { height: 6px; background: var(--surface2); border-radius: 99px; overflow: hidden; }
  .progress-fill { height: 100%; background: linear-gradient(90deg, var(--accent), var(--accent3)); border-radius: 99px; transition: width 1s ease; }

  /* ── TABLE ── */
  .table-wrap { overflow-x: auto; margin: 12px 0; }
  table { width: 100%; border-collapse: collapse; font-size: 13px; }
  th {
    background: var(--surface2);
    padding: 10px 12px;
    text-align: left;
    font-family: 'Syne', sans-serif;
    font-size: 12px;
    color: var(--accent2);
    border-bottom: 1px solid var(--border);
  }
  td { padding: 9px 12px; border-bottom: 1px solid rgba(255,255,255,.04); }
  tr:last-child td { border-bottom: none; }

  /* ── BACK TO TOP ── */
  .scroll-top {
    position: fixed;
    bottom: 20px;
    right: 16px;
    width: 42px; height: 42px;
    background: var(--accent);
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    cursor: pointer;
    box-shadow: 0 4px 20px rgba(255,75,110,.4);
    font-size: 18px;
    z-index: 100;
    opacity: 0;
    transition: opacity .3s;
  }
  .scroll-top.visible { opacity: 1; }

  /* ── FOOTER ── */
  footer {
    text-align: center;
    padding: 30px 20px;
    border-top: 1px solid var(--border);
    font-size: 12px;
    color: var(--muted);
  }
</style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <div class="badge">📱 Otimizado para Termux · Mobile First</div>
  <h1>Streamlit<br><span>Academy</span></h1>
  <p>Curso completo do zero ao avançado com exercícios, exemplos reais e material didático profissional.</p>
  <div class="stats">
    <div class="stat"><div class="stat-n">8</div><div class="stat-l">Módulos</div></div>
    <div class="stat"><div class="stat-n">40+</div><div class="stat-l">Exercícios</div></div>
    <div class="stat"><div class="stat-n">100%</div><div class="stat-l">Termux OK</div></div>
    <div class="stat"><div class="stat-n">Real</div><div class="stat-l">Projetos - Claudio Marinho</div></div>
  </div>
</div>

<!-- NAV TABS -->
<div class="nav-tabs">
  <button class="tab-btn active" onclick="showPanel('modulos')">📚 Módulos</button>
  <button class="tab-btn" onclick="showPanel('cheatsheet')">⚡ Cheatsheet</button>
  <button class="tab-btn" onclick="showPanel('projetos')">🚀 Projetos</button>
  <button class="tab-btn" onclick="showPanel('termux')">📱 Termux</button>
</div>

<!-- ════════════════════════════════════
     PAINEL: MÓDULOS
     ════════════════════════════════════ -->
<div id="panel-modulos" class="panel active">

  <!-- MÓDULO 0 -->
  <div class="module-card" onclick="toggleModule(this)">
    <div class="module-header">
      <div class="module-num">00</div>
      <div class="module-info">
        <div class="module-title">Configuração no Termux</div>
        <div class="module-sub">Ambiente, instalação e primeiro app</div>
      </div>
      <span class="module-arrow">›</span>
    </div>
    <div class="module-body">

      <div class="termux-box">
        <div class="termux-title">📱 Comandos Termux — Execute no seu terminal</div>
        <div class="code-block">
          <div class="code-header"><span class="code-lang">BASH</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
          <pre><span class="cm"># Atualizar pacotes</span>
pkg update && pkg upgrade -y

<span class="cm"># Instalar Python e pip</span>
pkg install python -y

<span class="cm"># Instalar Streamlit</span>
pip install streamlit

<span class="cm"># Verificar instalação</span>
streamlit --version

<span class="cm"># Criar pasta do projeto</span>
mkdir ~/meu_streamlit
cd ~/meu_streamlit</pre>
        </div>
      </div>

      <div class="section-title">🚀 Primeiro App (app.py)</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="cm"># Título da página</span>
<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"🎉 Meu Primeiro App!"</span>)

<span class="cm"># Texto simples</span>
<span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Olá, mundo! Streamlit funcionando!"</span>)

<span class="cm"># Input do usuário</span>
nome <span class="op">=</span> <span class="nb">st</span>.<span class="fn">text_input</span>(<span class="st">"Qual é o seu nome?"</span>)

<span class="kw">if</span> nome:
    <span class="nb">st</span>.<span class="fn">success</span>(<span class="st">f"Bem-vindo, {nome}! 👋"</span>)</pre>
      </div>

      <div class="termux-box">
        <div class="termux-title">▶ Como Executar</div>
        <div class="code-block">
          <div class="code-header"><span class="code-lang">BASH</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
          <pre><span class="cm"># Rodar o app</span>
streamlit run app.py

<span class="cm"># Abrir no navegador do celular:</span>
<span class="cm"># http://localhost:8501</span></pre>
        </div>
      </div>

      <div class="callout callout-tip">
        <span class="callout-icon">💡 Dica Termux</span>
        Use o navegador do seu celular e acesse <strong>localhost:8501</strong>. O app atualiza automaticamente quando você salva o arquivo!
      </div>

      <div class="exercise-card">
        <div class="exercise-title">🏠 Tarefa de Casa <span class="ex-badge">MÓDULO 00</span></div>
        <ol class="exercise-list">
          <li>Instale Streamlit no Termux seguindo os comandos acima</li>
          <li>Crie o arquivo <code>app.py</code> e execute-o com sucesso</li>
          <li>Modifique o app para exibir também a sua idade após digitar o nome</li>
          <li><strong>Desafio:</strong> Adicione uma mensagem diferente para diferentes nomes digitados</li>
        </ol>
      </div>
    </div>
  </div>

  <!-- MÓDULO 1 -->
  <div class="module-card" onclick="toggleModule(this)">
    <div class="module-header">
      <div class="module-num">01</div>
      <div class="module-info">
        <div class="module-title">Elementos de Texto e Layout</div>
        <div class="module-sub">st.write, markdown, colunas, sidebar</div>
      </div>
      <span class="module-arrow">›</span>
    </div>
    <div class="module-body">

      <div class="section-title">📝 Elementos de Texto</div>
      <p>Streamlit oferece várias funções para exibir texto com diferentes estilos e níveis hierárquicos.</p>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"Título Principal"</span>)          <span class="cm"># H1</span>
<span class="nb">st</span>.<span class="fn">header</span>(<span class="st">"Cabeçalho"</span>)               <span class="cm"># H2</span>
<span class="nb">st</span>.<span class="fn">subheader</span>(<span class="st">"Subcabeçalho"</span>)         <span class="cm"># H3</span>
<span class="nb">st</span>.<span class="fn">text</span>(<span class="st">"Texto simples"</span>)             <span class="cm"># Monoespaçado</span>
<span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Texto geral, aceita **markdown**"</span>)

<span class="cm"># Markdown completo</span>
<span class="nb">st</span>.<span class="fn">markdown</span>(<span class="st">"""
### Formatação Markdown
- **Negrito**, *itálico*, `código inline`
- [Link](https://streamlit.io)
- > Citação
"""</span>)

<span class="cm"># Código formatado</span>
<span class="nb">st</span>.<span class="fn">code</span>(<span class="st">"print('Hello!')"</span>, language<span class="op">=</span><span class="st">"python"</span>)

<span class="cm"># Fórmulas matemáticas (LaTeX)</span>
<span class="nb">st</span>.<span class="fn">latex</span>(<span class="st">r"E = mc^2"</span>)</pre>
      </div>

      <div class="section-title">📐 Layout com Colunas</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="cm"># Duas colunas iguais</span>
col1, col2 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>(<span class="nm">2</span>)

<span class="kw">with</span> col1:
    <span class="nb">st</span>.<span class="fn">header</span>(<span class="st">"Coluna 1"</span>)
    <span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Conteúdo à esquerda"</span>)

<span class="kw">with</span> col2:
    <span class="nb">st</span>.<span class="fn">header</span>(<span class="st">"Coluna 2"</span>)
    <span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Conteúdo à direita"</span>)

<span class="cm"># Colunas com proporções diferentes (2:1:1)</span>
c1, c2, c3 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>([<span class="nm">2</span>, <span class="nm">1</span>, <span class="nm">1</span>])

<span class="cm"># Sidebar (barra lateral)</span>
<span class="nb">st</span>.sidebar.<span class="fn">title</span>(<span class="st">"Menu"</span>)
opcao <span class="op">=</span> <span class="nb">st</span>.sidebar.<span class="fn">selectbox</span>(<span class="st">"Ir para"</span>, [<span class="st">"Home"</span>, <span class="st">"Sobre"</span>])

<span class="cm"># Expander (acordeão)</span>
<span class="kw">with</span> <span class="nb">st</span>.<span class="fn">expander</span>(<span class="st">"Clique para expandir"</span>):
    <span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Conteúdo oculto aqui!"</span>)</pre>
      </div>

      <div class="section-title">📦 Container e Tabs</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="cm"># Abas (Tabs) — muito útil no mobile!</span>
tab1, tab2, tab3 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">tabs</span>([<span class="st">"📊 Dados"</span>, <span class="st">"📈 Gráfico"</span>, <span class="st">"ℹ️ Info"</span>])

<span class="kw">with</span> tab1:
    <span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Tabela de dados aqui"</span>)

<span class="kw">with</span> tab2:
    <span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Gráfico aqui"</span>)

<span class="kw">with</span> tab3:
    <span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Informações aqui"</span>)</pre>
      </div>

      <div class="exercise-card">
        <div class="exercise-title">🏠 Tarefa de Casa <span class="ex-badge">MÓDULO 01</span></div>
        <ol class="exercise-list">
          <li>Crie uma página com título, cabeçalho e pelo menos 3 parágrafos usando markdown</li>
          <li>Adicione uma sidebar com seu nome e uma descrição do app</li>
          <li>Crie um layout de 3 colunas exibindo nome, idade e cidade</li>
          <li>Use <code>st.tabs()</code> para criar 3 abas: "Sobre Mim", "Hobbies" e "Contato"</li>
          <li><strong>Desafio:</strong> Crie um mini currículo usando todos os elementos aprendidos</li>
        </ol>
      </div>
    </div>
  </div>

  <!-- MÓDULO 2 -->
  <div class="module-card" onclick="toggleModule(this)">
    <div class="module-header">
      <div class="module-num">02</div>
      <div class="module-info">
        <div class="module-title">Widgets de Entrada</div>
        <div class="module-sub">Inputs, botões, sliders, selects</div>
      </div>
      <span class="module-arrow">›</span>
    </div>
    <div class="module-body">

      <div class="section-title">🎛️ Todos os Widgets</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="cm"># ── Texto ──</span>
nome <span class="op">=</span> <span class="nb">st</span>.<span class="fn">text_input</span>(<span class="st">"Nome"</span>, placeholder<span class="op">=</span><span class="st">"Digite seu nome"</span>)
bio  <span class="op">=</span> <span class="nb">st</span>.<span class="fn">text_area</span>(<span class="st">"Biografia"</span>, height<span class="op">=</span><span class="nm">100</span>)

<span class="cm"># ── Numérico ──</span>
idade  <span class="op">=</span> <span class="nb">st</span>.<span class="fn">number_input</span>(<span class="st">"Idade"</span>, min_value<span class="op">=</span><span class="nm">0</span>, max_value<span class="op">=</span><span class="nm">120</span>, value<span class="op">=</span><span class="nm">25</span>)
volume <span class="op">=</span> <span class="nb">st</span>.<span class="fn">slider</span>(<span class="st">"Volume"</span>, <span class="nm">0</span>, <span class="nm">100</span>, <span class="nm">50</span>)

<span class="cm"># Range slider</span>
faixa <span class="op">=</span> <span class="nb">st</span>.<span class="fn">slider</span>(<span class="st">"Faixa de preço"</span>, <span class="nm">0</span>, <span class="nm">1000</span>, (<span class="nm">100</span>, <span class="nm">500</span>))

<span class="cm"># ── Seleção ──</span>
cidade <span class="op">=</span> <span class="nb">st</span>.<span class="fn">selectbox</span>(<span class="st">"Cidade"</span>, [<span class="st">"SP"</span>, <span class="st">"RJ"</span>, <span class="st">"BH"</span>, <span class="st">"POA"</span>])
frutas <span class="op">=</span> <span class="nb">st</span>.<span class="fn">multiselect</span>(<span class="st">"Frutas favoritas"</span>, [<span class="st">"🍎 Maçã"</span>, <span class="st">"🍊 Laranja"</span>, <span class="st">"🍇 Uva"</span>])

<span class="cm"># ── Toggle / Checkbox ──</span>
aceito <span class="op">=</span> <span class="nb">st</span>.<span class="fn">checkbox</span>(<span class="st">"Aceito os termos"</span>)
modo   <span class="op">=</span> <span class="nb">st</span>.<span class="fn">toggle</span>(<span class="st">"Modo escuro"</span>)

<span class="cm"># ── Radio ──</span>
plano <span class="op">=</span> <span class="nb">st</span>.<span class="fn">radio</span>(<span class="st">"Plano"</span>, [<span class="st">"Free"</span>, <span class="st">"Pro"</span>, <span class="st">"Enterprise"</span>], horizontal<span class="op">=</span><span class="kw">True</span>)

<span class="cm"># ── Data e hora ──</span>
<span class="kw">import</span> datetime
data  <span class="op">=</span> <span class="nb">st</span>.<span class="fn">date_input</span>(<span class="st">"Data"</span>)
hora  <span class="op">=</span> <span class="nb">st</span>.<span class="fn">time_input</span>(<span class="st">"Hora"</span>)

<span class="cm"># ── Botão ──</span>
<span class="kw">if</span> <span class="nb">st</span>.<span class="fn">button</span>(<span class="st">"🚀 Enviar"</span>, type<span class="op">=</span><span class="st">"primary"</span>):
    <span class="nb">st</span>.<span class="fn">success</span>(<span class="st">"Formulário enviado!"</span>)
    <span class="nb">st</span>.<span class="fn">write</span>(<span class="st">f"Nome: {nome}, Cidade: {cidade}"</span>)</pre>
      </div>

      <div class="callout callout-info">
        <span class="callout-icon">ℹ️ Como os Widgets Funcionam</span>
        Cada widget <strong>retorna um valor</strong>. Quando o usuário interage, o Streamlit re-executa o script inteiro com os novos valores. É simples e poderoso!
      </div>

      <div class="section-title">🧮 Projeto Prático — Calculadora IMC</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON — calculadora_imc.py</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"🏋️ Calculadora de IMC"</span>)

col1, col2 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>(<span class="nm">2</span>)

<span class="kw">with</span> col1:
    peso <span class="op">=</span> <span class="nb">st</span>.<span class="fn">number_input</span>(<span class="st">"Peso (kg)"</span>, <span class="nm">30.0</span>, <span class="nm">200.0</span>, <span class="nm">70.0</span>)

<span class="kw">with</span> col2:
    altura <span class="op">=</span> <span class="nb">st</span>.<span class="fn">number_input</span>(<span class="st">"Altura (m)"</span>, <span class="nm">1.0</span>, <span class="nm">2.5</span>, <span class="nm">1.70</span>)

<span class="kw">if</span> <span class="nb">st</span>.<span class="fn">button</span>(<span class="st">"Calcular"</span>, type<span class="op">=</span><span class="st">"primary"</span>):
    imc <span class="op">=</span> peso <span class="op">/</span> (altura <span class="op">**</span> <span class="nm">2</span>)
    <span class="nb">st</span>.<span class="fn">metric</span>(<span class="st">"Seu IMC"</span>, <span class="st">f"{imc:.1f}"</span>)

    <span class="kw">if</span> imc <span class="op">&lt;</span> <span class="nm">18.5</span>:
        <span class="nb">st</span>.<span class="fn">warning</span>(<span class="st">"⚠️ Abaixo do peso"</span>)
    <span class="kw">elif</span> imc <span class="op">&lt;</span> <span class="nm">25</span>:
        <span class="nb">st</span>.<span class="fn">success</span>(<span class="st">"✅ Peso normal"</span>)
    <span class="kw">elif</span> imc <span class="op">&lt;</span> <span class="nm">30</span>:
        <span class="nb">st</span>.<span class="fn">warning</span>(<span class="st">"⚠️ Sobrepeso"</span>)
    <span class="kw">else</span>:
        <span class="nb">st</span>.<span class="fn">error</span>(<span class="st">"❌ Obesidade"</span>)</pre>
      </div>

      <div class="exercise-card">
        <div class="exercise-title">🏠 Tarefa de Casa <span class="ex-badge">MÓDULO 02</span></div>
        <ol class="exercise-list">
          <li>Reproduza a calculadora de IMC acima e teste no Termux</li>
          <li>Crie um formulário de cadastro com: nome, email, cidade (select), data de nascimento e um checkbox de aceite</li>
          <li>Crie uma calculadora de conversão: °C para °F usando slider</li>
          <li><strong>Desafio:</strong> Crie um app de enquete com <code>st.radio()</code> e exiba os resultados em tempo real com <code>st.metric()</code></li>
        </ol>
      </div>
    </div>
  </div>

  <!-- MÓDULO 3 -->
  <div class="module-card" onclick="toggleModule(this)">
    <div class="module-header">
      <div class="module-num">03</div>
      <div class="module-info">
        <div class="module-title">Gráficos e Visualização</div>
        <div class="module-sub">Matplotlib, Plotly, gráficos nativos</div>
      </div>
      <span class="module-arrow">›</span>
    </div>
    <div class="module-body">

      <div class="termux-box">
        <div class="termux-title">📱 Instalar bibliotecas</div>
        <div class="code-block">
          <div class="code-header"><span class="code-lang">BASH</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
          <pre>pip install matplotlib plotly pandas numpy</pre>
        </div>
      </div>

      <div class="section-title">📊 Gráficos Nativos (mais simples)</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> pandas <span class="kw">as</span> pd
<span class="kw">import</span> numpy <span class="kw">as</span> np

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"📊 Gráficos com Streamlit"</span>)

<span class="cm"># Dados de exemplo</span>
df <span class="op">=</span> pd.<span class="fn">DataFrame</span>({
    <span class="st">"mês"</span>: [<span class="st">"Jan"</span>, <span class="st">"Fev"</span>, <span class="st">"Mar"</span>, <span class="st">"Abr"</span>, <span class="st">"Mai"</span>],
    <span class="st">"vendas"</span>: [<span class="nm">120</span>, <span class="nm">145</span>, <span class="nm">98</span>, <span class="nm">175</span>, <span class="nm">210</span>],
    <span class="st">"lucro"</span>:  [<span class="nm">30</span>,  <span class="nm">45</span>,  <span class="nm">20</span>,  <span class="nm">60</span>,  <span class="nm">80</span>]
})

<span class="cm"># Gráfico de linha nativo</span>
<span class="nb">st</span>.<span class="fn">subheader</span>(<span class="st">"Linha"</span>)
<span class="nb">st</span>.<span class="fn">line_chart</span>(df.<span class="fn">set_index</span>(<span class="st">"mês"</span>))

<span class="cm"># Gráfico de barras nativo</span>
<span class="nb">st</span>.<span class="fn">subheader</span>(<span class="st">"Barras"</span>)
<span class="nb">st</span>.<span class="fn">bar_chart</span>(df.<span class="fn">set_index</span>(<span class="st">"mês"</span>)[<span class="st">"vendas"</span>])

<span class="cm"># Gráfico de área nativo</span>
<span class="nb">st</span>.<span class="fn">subheader</span>(<span class="st">"Área"</span>)
<span class="nb">st</span>.<span class="fn">area_chart</span>(df.<span class="fn">set_index</span>(<span class="st">"mês"</span>))</pre>
      </div>

      <div class="section-title">📈 Plotly (interativo)</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> plotly.express <span class="kw">as</span> px
<span class="kw">import</span> pandas <span class="kw">as</span> pd

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"📈 Gráficos Plotly Interativos"</span>)

<span class="cm"># Dataset embutido</span>
df <span class="op">=</span> px.data.<span class="fn">gapminder</span>().<span class="fn">query</span>(<span class="st">"year == 2007"</span>)

<span class="cm"># Scatter plot com zoom e hover</span>
fig <span class="op">=</span> px.<span class="fn">scatter</span>(
    df, x<span class="op">=</span><span class="st">"gdpPercap"</span>, y<span class="op">=</span><span class="st">"lifeExp"</span>,
    size<span class="op">=</span><span class="st">"pop"</span>, color<span class="op">=</span><span class="st">"continent"</span>,
    hover_name<span class="op">=</span><span class="st">"country"</span>, log_x<span class="op">=</span><span class="kw">True</span>,
    title<span class="op">=</span><span class="st">"PIB vs Expectativa de Vida (2007)"</span>
)
<span class="nb">st</span>.<span class="fn">plotly_chart</span>(fig, use_container_width<span class="op">=</span><span class="kw">True</span>)

<span class="cm"># Gráfico de pizza</span>
vendas_cidade <span class="op">=</span> pd.<span class="fn">DataFrame</span>({
    <span class="st">"Cidade"</span>: [<span class="st">"SP"</span>, <span class="st">"RJ"</span>, <span class="st">"BH"</span>, <span class="st">"RS"</span>],
    <span class="st">"Vendas"</span>: [<span class="nm">450</span>, <span class="nm">320</span>, <span class="nm">180</span>, <span class="nm">150</span>]
})
fig2 <span class="op">=</span> px.<span class="fn">pie</span>(vendas_cidade, values<span class="op">=</span><span class="st">"Vendas"</span>, names<span class="op">=</span><span class="st">"Cidade"</span>)
<span class="nb">st</span>.<span class="fn">plotly_chart</span>(fig2, use_container_width<span class="op">=</span><span class="kw">True</span>)</pre>
      </div>

      <div class="exercise-card">
        <div class="exercise-title">🏠 Tarefa de Casa <span class="ex-badge">MÓDULO 03</span></div>
        <ol class="exercise-list">
          <li>Crie um dashboard com gráfico de linha mostrando temperatura dos últimos 7 dias (invente os dados)</li>
          <li>Use <code>st.slider()</code> para filtrar o período exibido no gráfico</li>
          <li>Adicione um gráfico de barras comparando duas variáveis</li>
          <li><strong>Desafio:</strong> Crie um app onde o usuário digita valores e o gráfico atualiza em tempo real</li>
        </ol>
      </div>
    </div>
  </div>

  <!-- MÓDULO 4 -->
  <div class="module-card" onclick="toggleModule(this)">
    <div class="module-header">
      <div class="module-num">04</div>
      <div class="module-info">
        <div class="module-title">Pandas & DataFrames</div>
        <div class="module-sub">Tabelas, filtros, upload de dados</div>
      </div>
      <span class="module-arrow">›</span>
    </div>
    <div class="module-body">

      <div class="section-title">🗃️ Exibindo DataFrames</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> pandas <span class="kw">as</span> pd

<span class="cm"># Criar DataFrame</span>
df <span class="op">=</span> pd.<span class="fn">DataFrame</span>({
    <span class="st">"Nome"</span>:    [<span class="st">"Ana"</span>, <span class="st">"Carlos"</span>, <span class="st">"Maria"</span>, <span class="st">"João"</span>],
    <span class="st">"Idade"</span>:   [<span class="nm">28</span>, <span class="nm">35</span>, <span class="nm">22</span>, <span class="nm">42</span>],
    <span class="st">"Salário"</span>: [<span class="nm">5000</span>, <span class="nm">8000</span>, <span class="nm">3500</span>, <span class="nm">12000</span>],
    <span class="st">"Cidade"</span>:  [<span class="st">"SP"</span>, <span class="st">"RJ"</span>, <span class="st">"SP"</span>, <span class="st">"BH"</span>]
})

<span class="cm"># Tabela estática</span>
<span class="nb">st</span>.<span class="fn">table</span>(df)

<span class="cm"># Tabela interativa (com ordenação)</span>
<span class="nb">st</span>.<span class="fn">dataframe</span>(df, use_container_width<span class="op">=</span><span class="kw">True</span>)

<span class="cm"># Tabela editável!</span>
df_edit <span class="op">=</span> <span class="nb">st</span>.<span class="fn">data_editor</span>(df, num_rows<span class="op">=</span><span class="st">"dynamic"</span>)
<span class="nb">st</span>.<span class="fn">write</span>(<span class="st">"Dados editados:"</span>, df_edit)</pre>
      </div>

      <div class="section-title">🔍 Filtros Interativos</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON — app_filtros.py</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> pandas <span class="kw">as</span> pd

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"🔍 Filtros em DataFrame"</span>)

<span class="cm"># Dataset</span>
df <span class="op">=</span> pd.<span class="fn">DataFrame</span>({
    <span class="st">"produto"</span>: [<span class="st">"Notebook"</span>,<span class="st">"Mouse"</span>,<span class="st">"Teclado"</span>,<span class="st">"Monitor"</span>,<span class="st">"Headset"</span>],
    <span class="st">"preço"</span>:   [<span class="nm">3500</span>, <span class="nm">120</span>, <span class="nm">280</span>, <span class="nm">1200</span>, <span class="nm">450</span>],
    <span class="st">"estoque"</span>: [<span class="nm">10</span>, <span class="nm">50</span>, <span class="nm">30</span>, <span class="nm">15</span>, <span class="nm">25</span>],
    <span class="st">"categoria"</span>:[<span class="st">"PC"</span>,<span class="st">"PC"</span>,<span class="st">"PC"</span>,<span class="st">"PC"</span>,<span class="st">"Áudio"</span>]
})

<span class="cm"># Filtros na sidebar</span>
<span class="kw">with</span> <span class="nb">st</span>.sidebar:
    <span class="nb">st</span>.<span class="fn">header</span>(<span class="st">"⚙️ Filtros"</span>)
    
    preco_max <span class="op">=</span> <span class="nb">st</span>.<span class="fn">slider</span>(
        <span class="st">"Preço máximo"</span>, 
        int(df.preço.<span class="fn">min</span>()), 
        int(df.preço.<span class="fn">max</span>()), 
        int(df.preço.<span class="fn">max</span>())
    )
    
    cats <span class="op">=</span> <span class="nb">st</span>.<span class="fn">multiselect</span>(
        <span class="st">"Categoria"</span>, 
        df.categoria.<span class="fn">unique</span>(), 
        default<span class="op">=</span>df.categoria.<span class="fn">unique</span>()
    )

<span class="cm"># Aplicar filtros</span>
df_filtrado <span class="op">=</span> df[
    (df.preço <span class="op">&lt;=</span> preco_max) <span class="op">&amp;</span>
    (df.categoria.<span class="fn">isin</span>(cats))
]

<span class="nb">st</span>.<span class="fn">metric</span>(<span class="st">"Produtos encontrados"</span>, len(df_filtrado))
<span class="nb">st</span>.<span class="fn">dataframe</span>(df_filtrado, use_container_width<span class="op">=</span><span class="kw">True</span>)</pre>
      </div>

      <div class="section-title">📤 Upload de Arquivo CSV</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> pandas <span class="kw">as</span> pd

arquivo <span class="op">=</span> <span class="nb">st</span>.<span class="fn">file_uploader</span>(<span class="st">"📂 Carregue seu CSV"</span>, type<span class="op">=</span>[<span class="st">"csv"</span>])

<span class="kw">if</span> arquivo:
    df <span class="op">=</span> pd.<span class="fn">read_csv</span>(arquivo)
    
    <span class="nb">st</span>.<span class="fn">success</span>(<span class="st">f"✅ {len(df)} linhas carregadas!"</span>)
    
    col1, col2, col3 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>(<span class="nm">3</span>)
    col1.<span class="fn">metric</span>(<span class="st">"Linhas"</span>, df.<span class="fn">shape</span>[<span class="nm">0</span>])
    col2.<span class="fn">metric</span>(<span class="st">"Colunas"</span>, df.<span class="fn">shape</span>[<span class="nm">1</span>])
    col3.<span class="fn">metric</span>(<span class="st">"Tamanho"</span>, <span class="st">f"{arquivo.size // 1024} KB"</span>)
    
    <span class="nb">st</span>.<span class="fn">dataframe</span>(df.head(<span class="nm">10</span>))</pre>
      </div>

      <div class="exercise-card">
        <div class="exercise-title">🏠 Tarefa de Casa <span class="ex-badge">MÓDULO 04</span></div>
        <ol class="exercise-list">
          <li>Crie um app com tabela de 10 produtos com preço, categoria e estoque</li>
          <li>Adicione filtros por faixa de preço e por categoria</li>
          <li>Mostre métricas: total de produtos, preço médio, produto mais caro</li>
          <li><strong>Desafio:</strong> Implemente busca por texto no nome do produto usando <code>st.text_input()</code> + <code>str.contains()</code></li>
        </ol>
      </div>
    </div>
  </div>

  <!-- MÓDULO 5 -->
  <div class="module-card" onclick="toggleModule(this)">
    <div class="module-header">
      <div class="module-num">05</div>
      <div class="module-info">
        <div class="module-title">Session State & Reatividade</div>
        <div class="module-sub">Estado, callbacks, formulários</div>
      </div>
      <span class="module-arrow">›</span>
    </div>
    <div class="module-body">

      <div class="callout callout-info">
        <span class="callout-icon">🧠 Conceito Fundamental</span>
        Streamlit re-executa o script <strong>inteiro</strong> cada vez que o usuário interage. O <code>st.session_state</code> permite persistir dados entre essas execuções.
      </div>

      <div class="section-title">💾 Session State Básico</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="cm"># Inicializar estado (sempre verificar antes)</span>
<span class="kw">if</span> <span class="st">"contador"</span> <span class="kw">not in</span> <span class="nb">st</span>.session_state:
    <span class="nb">st</span>.session_state.contador <span class="op">=</span> <span class="nm">0</span>

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"🔢 Contador Persistente"</span>)
<span class="nb">st</span>.<span class="fn">metric</span>(<span class="st">"Contagem atual"</span>, <span class="nb">st</span>.session_state.contador)

col1, col2, col3 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>(<span class="nm">3</span>)

<span class="kw">if</span> col1.<span class="fn">button</span>(<span class="st">"➕ +1"</span>):
    <span class="nb">st</span>.session_state.contador <span class="op">+=</span> <span class="nm">1</span>

<span class="kw">if</span> col2.<span class="fn">button</span>(<span class="st">"➖ -1"</span>):
    <span class="nb">st</span>.session_state.contador <span class="op">-=</span> <span class="nm">1</span>

<span class="kw">if</span> col3.<span class="fn">button</span>(<span class="st">"🔄 Zerar"</span>):
    <span class="nb">st</span>.session_state.contador <span class="op">=</span> <span class="nm">0</span></pre>
      </div>

      <div class="section-title">🛒 Projeto Prático — Carrinho de Compras</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON — carrinho.py</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="cm"># Inicializar carrinho</span>
<span class="kw">if</span> <span class="st">"carrinho"</span> <span class="kw">not in</span> <span class="nb">st</span>.session_state:
    <span class="nb">st</span>.session_state.carrinho <span class="op">=</span> []

produtos <span class="op">=</span> {
    <span class="st">"☕ Café"</span>: <span class="nm">8.90</span>,
    <span class="st">"🍕 Pizza"</span>: <span class="nm">35.00</span>,
    <span class="st">"🍺 Cerveja"</span>: <span class="nm">12.00</span>,
    <span class="st">"🍔 Hambúrguer"</span>: <span class="nm">28.00</span>
}

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"🛒 Carrinho de Compras"</span>)

<span class="cm"># Adicionar produto</span>
col1, col2 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>([<span class="nm">3</span>, <span class="nm">1</span>])
escolha <span class="op">=</span> col1.<span class="fn">selectbox</span>(<span class="st">"Produto"</span>, list(produtos.keys()))

<span class="kw">if</span> col2.<span class="fn">button</span>(<span class="st">"Adicionar"</span>, type<span class="op">=</span><span class="st">"primary"</span>):
    <span class="nb">st</span>.session_state.carrinho.<span class="fn">append</span>({
        <span class="st">"item"</span>: escolha,
        <span class="st">"preço"</span>: produtos[escolha]
    })

<span class="cm"># Exibir carrinho</span>
<span class="kw">if</span> <span class="nb">st</span>.session_state.carrinho:
    <span class="nb">st</span>.<span class="fn">subheader</span>(<span class="st">"Seu Carrinho"</span>)
    total <span class="op">=</span> <span class="nm">0</span>
    <span class="kw">for</span> i, item <span class="kw">in</span> <span class="fn">enumerate</span>(<span class="nb">st</span>.session_state.carrinho):
        c1, c2, c3 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>([<span class="nm">3</span>, <span class="nm">1</span>, <span class="nm">1</span>])
        c1.<span class="fn">write</span>(item[<span class="st">"item"</span>])
        c2.<span class="fn">write</span>(<span class="st">f"R$ {item['preço']:.2f}"</span>)
        total <span class="op">+=</span> item[<span class="st">"preço"</span>]
    
    <span class="nb">st</span>.<span class="fn">divider</span>()
    <span class="nb">st</span>.<span class="fn">metric</span>(<span class="st">"Total"</span>, <span class="st">f"R$ {total:.2f}"</span>)
    
    <span class="kw">if</span> <span class="nb">st</span>.<span class="fn">button</span>(<span class="st">"🗑️ Limpar carrinho"</span>):
        <span class="nb">st</span>.session_state.carrinho <span class="op">=</span> []
        <span class="nb">st</span>.<span class="fn">rerun</span>()</pre>
      </div>

      <div class="exercise-card">
        <div class="exercise-title">🏠 Tarefa de Casa <span class="ex-badge">MÓDULO 05</span></div>
        <ol class="exercise-list">
          <li>Implemente o carrinho de compras acima e teste</li>
          <li>Adicione a funcionalidade de remover itens individuais</li>
          <li>Crie um app de quiz com 3 perguntas usando session_state para guardar respostas e calcular pontuação final</li>
          <li><strong>Desafio:</strong> Crie um app de lista de tarefas (To-Do List) com adicionar, marcar como feito e deletar</li>
        </ol>
      </div>
    </div>
  </div>

  <!-- MÓDULO 6 -->
  <div class="module-card" onclick="toggleModule(this)">
    <div class="module-header">
      <div class="module-num">06</div>
      <div class="module-info">
        <div class="module-title">APIs e Dados Externos</div>
        <div class="module-sub">Requests, JSON, cache, tempo real</div>
      </div>
      <span class="module-arrow">›</span>
    </div>
    <div class="module-body">

      <div class="termux-box">
        <div class="termux-title">📱 Instalar no Termux</div>
        <div class="code-block">
          <div class="code-header"><span class="code-lang">BASH</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
          <pre>pip install requests</pre>
        </div>
      </div>

      <div class="section-title">🌐 Consumindo API com Cache</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON — api_pokemon.py</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> requests

<span class="cm"># @st.cache_data → chama a API apenas 1x</span>
<span class="cm"># Os dados ficam em cache por 1 hora</span>
<span class="nb">@st</span>.<span class="fn">cache_data</span>(ttl<span class="op">=</span><span class="nm">3600</span>)
<span class="kw">def</span> <span class="fn">buscar_pokemon</span>(nome):
    url <span class="op">=</span> <span class="st">f"https://pokeapi.co/api/v2/pokemon/{nome.lower()}"</span>
    r <span class="op">=</span> requests.<span class="fn">get</span>(url)
    <span class="kw">if</span> r.status_code <span class="op">==</span> <span class="nm">200</span>:
        <span class="kw">return</span> r.<span class="fn">json</span>()
    <span class="kw">return</span> <span class="kw">None</span>

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"🎮 Pokédex Streamlit"</span>)

nome <span class="op">=</span> <span class="nb">st</span>.<span class="fn">text_input</span>(<span class="st">"Nome do Pokémon"</span>, <span class="st">"pikachu"</span>)

<span class="kw">if</span> <span class="nb">st</span>.<span class="fn">button</span>(<span class="st">"🔍 Buscar"</span>, type<span class="op">=</span><span class="st">"primary"</span>):
    <span class="kw">with</span> <span class="nb">st</span>.<span class="fn">spinner</span>(<span class="st">"Buscando..."</span>):
        dados <span class="op">=</span> <span class="fn">buscar_pokemon</span>(nome)
    
    <span class="kw">if</span> dados:
        col1, col2 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>(<span class="nm">2</span>)
        col1.<span class="fn">image</span>(dados[<span class="st">"sprites"</span>][<span class="st">"front_default"</span>], width<span class="op">=</span><span class="nm">150</span>)
        col2.<span class="fn">metric</span>(<span class="st">"Altura"</span>, <span class="st">f"{dados['height']/10}m"</span>)
        col2.<span class="fn">metric</span>(<span class="st">"Peso"</span>, <span class="st">f"{dados['weight']/10}kg"</span>)
        
        tipos <span class="op">=</span> [t[<span class="st">"type"</span>][<span class="st">"name"</span>] <span class="kw">for</span> t <span class="kw">in</span> dados[<span class="st">"types"</span>]]
        <span class="nb">st</span>.<span class="fn">write</span>(<span class="st">f"**Tipos:** {', '.join(tipos)}"</span>)
    <span class="kw">else</span>:
        <span class="nb">st</span>.<span class="fn">error</span>(<span class="st">"Pokémon não encontrado!"</span>)</pre>
      </div>

      <div class="section-title">⏱️ Auto-atualização (Real-time)</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> time
<span class="kw">import</span> random

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"📡 Dashboard Tempo Real"</span>)

<span class="cm"># Placeholder que será atualizado</span>
placeholder <span class="op">=</span> <span class="nb">st</span>.<span class="fn">empty</span>()

<span class="kw">for</span> i <span class="kw">in</span> <span class="fn">range</span>(<span class="nm">30</span>):
    temperatura <span class="op">=</span> random.<span class="fn">uniform</span>(<span class="nm">20</span>, <span class="nm">30</span>)
    
    <span class="kw">with</span> placeholder.<span class="fn">container</span>():
        <span class="nb">st</span>.<span class="fn">metric</span>(<span class="st">"🌡️ Temperatura"</span>, <span class="st">f"{temperatura:.1f}°C"</span>)
        <span class="nb">st</span>.<span class="fn">progress</span>((temperatura <span class="op">-</span> <span class="nm">20</span>) <span class="op">/</span> <span class="nm">10</span>)
    
    time.<span class="fn">sleep</span>(<span class="nm">1</span>)</pre>
      </div>

      <div class="exercise-card">
        <div class="exercise-title">🏠 Tarefa de Casa <span class="ex-badge">MÓDULO 06</span></div>
        <ol class="exercise-list">
          <li>Implemente a Pokédex e adicione uma tabela com todos os golpes do Pokémon</li>
          <li>Crie um app que busca cotação do dólar em uma API pública</li>
          <li>Use <code>@st.cache_data</code> para evitar chamadas repetidas</li>
          <li><strong>Desafio:</strong> Crie um dashboard de clima usando a API Open-Meteo (gratuita, sem chave)</li>
        </ol>
      </div>
    </div>
  </div>

  <!-- MÓDULO 7 -->
  <div class="module-card" onclick="toggleModule(this)">
    <div class="module-header">
      <div class="module-num">07</div>
      <div class="module-info">
        <div class="module-title">Projeto Final — Dashboard Completo</div>
        <div class="module-sub">App profissional, multipage, deploy</div>
      </div>
      <span class="module-arrow">›</span>
    </div>
    <div class="module-body">

      <div class="section-title">📁 Estrutura Multipage</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">ESTRUTURA DE PASTAS</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre>meu_app/
├── app.py              ← Página principal
├── pages/
│   ├── 1_📊_dados.py   ← Página Dados
│   ├── 2_📈_graficos.py ← Página Gráficos  
│   └── 3_ℹ️_sobre.py   ← Página Sobre
└── utils/
    └── helpers.py      ← Funções reutilizáveis</pre>
      </div>

      <div class="section-title">🏆 Dashboard Financeiro Completo</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON — app.py (PROJETO FINAL)</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> pandas <span class="kw">as</span> pd
<span class="kw">import</span> plotly.express <span class="kw">as</span> px
<span class="kw">import</span> numpy <span class="kw">as</span> np
<span class="kw">from</span> datetime <span class="kw">import</span> date, timedelta

<span class="cm"># ── Configuração da página ──</span>
<span class="nb">st</span>.<span class="fn">set_page_config</span>(
    page_title<span class="op">=</span><span class="st">"💰 Dashboard Financeiro"</span>,
    page_icon<span class="op">=</span><span class="st">"💰"</span>,
    layout<span class="op">=</span><span class="st">"wide"</span>,
    initial_sidebar_state<span class="op">=</span><span class="st">"expanded"</span>
)

<span class="cm"># ── Estilo customizado ──</span>
<span class="nb">st</span>.<span class="fn">markdown</span>(<span class="st">"""
&lt;style&gt;
.metric-card {
    background: #1a2235;
    border-radius: 10px;
    padding: 16px;
    border: 1px solid #1e2d47;
}
&lt;/style&gt;
"""</span>, unsafe_allow_html<span class="op">=</span><span class="kw">True</span>)

<span class="cm"># ── Gerar dados fictícios ──</span>
<span class="nb">@st</span>.<span class="fn">cache_data</span>
<span class="kw">def</span> <span class="fn">gerar_dados</span>():
    datas <span class="op">=</span> [date(<span class="nm">2024</span>,<span class="nm">1</span>,<span class="nm">1</span>) <span class="op">+</span> timedelta(days<span class="op">=</span>i) <span class="kw">for</span> i <span class="kw">in</span> <span class="fn">range</span>(<span class="nm">365</span>)]
    np.random.<span class="fn">seed</span>(<span class="nm">42</span>)
    <span class="kw">return</span> pd.<span class="fn">DataFrame</span>({
        <span class="st">"data"</span>:   datas,
        <span class="st">"receita"</span>: np.random.<span class="fn">normal</span>(<span class="nm">10000</span>, <span class="nm">2000</span>, <span class="nm">365</span>).<span class="fn">cumsum</span>(),
        <span class="st">"despesa"</span>: np.random.<span class="fn">normal</span>(<span class="nm">7000</span>,  <span class="nm">1500</span>, <span class="nm">365</span>).<span class="fn">cumsum</span>(),
        <span class="st">"categoria"</span>: np.random.<span class="fn">choice</span>([<span class="st">"Vendas"</span>,<span class="st">"Serviços"</span>,<span class="st">"Outros"</span>], <span class="nm">365</span>)
    })

df <span class="op">=</span> <span class="fn">gerar_dados</span>()

<span class="cm"># ── Sidebar ──</span>
<span class="kw">with</span> <span class="nb">st</span>.sidebar:
    <span class="nb">st</span>.<span class="fn">image</span>(<span class="st">"https://via.placeholder.com/200x60?text=FinanceApp"</span>)
    data_ini <span class="op">=</span> <span class="nb">st</span>.<span class="fn">date_input</span>(<span class="st">"Data inicial"</span>, date(<span class="nm">2024</span>,<span class="nm">1</span>,<span class="nm">1</span>))
    data_fim <span class="op">=</span> <span class="nb">st</span>.<span class="fn">date_input</span>(<span class="st">"Data final"</span>,   date(<span class="nm">2024</span>,<span class="nm">12</span>,<span class="nm">31</span>))
    cats <span class="op">=</span> <span class="nb">st</span>.<span class="fn">multiselect</span>(<span class="st">"Categorias"</span>, df.categoria.<span class="fn">unique</span>(),
                           default<span class="op">=</span>df.categoria.<span class="fn">unique</span>())

<span class="cm"># Filtrar</span>
mask <span class="op">=</span> (df.data.<span class="fn">apply</span>(<span class="kw">lambda</span> x: x) <span class="op">&gt;=</span> pd.<span class="fn">Timestamp</span>(data_ini)) <span class="op">&amp;</span> \
       (df.data <span class="op">&lt;=</span> pd.<span class="fn">Timestamp</span>(data_fim)) <span class="op">&amp;</span> \
       (df.categoria.<span class="fn">isin</span>(cats))
df_f <span class="op">=</span> df[mask]

<span class="cm"># ── KPIs ──</span>
<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"💰 Dashboard Financeiro"</span>)

k1, k2, k3, k4 <span class="op">=</span> <span class="nb">st</span>.<span class="fn">columns</span>(<span class="nm">4</span>)
k1.<span class="fn">metric</span>(<span class="st">"Receita Total"</span>,  <span class="st">f"R$ {df_f.receita.<span class="fn">iloc[-1]</span>/1e6:.1f}M"</span>)
k2.<span class="fn">metric</span>(<span class="st">"Despesa Total"</span>,  <span class="st">f"R$ {df_f.despesa.<span class="fn">iloc[-1]</span>/1e6:.1f}M"</span>)
k3.<span class="fn">metric</span>(<span class="st">"Lucro"</span>, <span class="st">f"R$ {(df_f.receita-df_f.despesa).<span class="fn">iloc[-1]</span>/1e6:.1f}M"</span>, delta<span class="op">=</span><span class="st">"+12%"</span>)
k4.<span class="fn">metric</span>(<span class="st">"Registros"</span>, <span class="fn">len</span>(df_f))

<span class="cm"># ── Gráfico Principal ──</span>
fig <span class="op">=</span> px.<span class="fn">line</span>(df_f, x<span class="op">=</span><span class="st">"data"</span>, y<span class="op">=</span>[<span class="st">"receita"</span>,<span class="st">"despesa"</span>],
             title<span class="op">=</span><span class="st">"📈 Evolução Financeira"</span>,
             labels<span class="op">=</span>{<span class="st">"value"</span>:<span class="st">"R$"</span>,<span class="st">"data"</span>:<span class="st">"Data"</span>})
<span class="nb">st</span>.<span class="fn">plotly_chart</span>(fig, use_container_width<span class="op">=</span><span class="kw">True</span>)

<span class="cm"># ── Tabela ──</span>
<span class="nb">st</span>.<span class="fn">dataframe</span>(df_f.<span class="fn">tail</span>(<span class="nm">20</span>), use_container_width<span class="op">=</span><span class="kw">True</span>)</pre>
      </div>

      <div class="section-title">☁️ Deploy Gratuito no Streamlit Cloud</div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">BASH — Passos para Deploy</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="cm"># 1. Criar requirements.txt</span>
echo "streamlit
pandas
plotly
numpy" > requirements.txt

<span class="cm"># 2. Subir para GitHub</span>
git init
git add .
git commit -m "primeiro commit"
git remote add origin https://github.com/SEU_USER/SEU_REPO
git push -u origin main

<span class="cm"># 3. Acessar share.streamlit.io</span>
<span class="cm"># 4. Conectar repositório e fazer deploy!</span></pre>
      </div>

      <div class="exercise-card">
        <div class="exercise-title">🏆 Projeto Final <span class="ex-badge">CONCLUSÃO</span></div>
        <p style="color:#a0aec0;font-size:13px;margin-bottom:10px;">Crie um dos seguintes projetos completos:</p>
        <ol class="exercise-list">
          <li><strong>📊 Dashboard de Vendas:</strong> Dados CSV + filtros + 3 gráficos + KPIs + exportar</li>
          <li><strong>🌤️ App de Clima:</strong> API real + previsão + gráficos + mapa</li>
          <li><strong>🎮 Pokédex Avançada:</strong> Busca + comparação + favoritos + session state</li>
          <li><strong>📝 App de Finanças Pessoais:</strong> Registrar gastos + categorias + relatórios mensais</li>
          <li><strong>🤖 Chatbot Simples:</strong> Interface de chat com session state + respostas pré-programadas</li>
        </ol>
      </div>
    </div>
  </div>

</div><!-- /panel-modulos -->

<!-- ════════════════════════════════════
     PAINEL: CHEATSHEET
     ════════════════════════════════════ -->
<div id="panel-cheatsheet" class="panel">
  <h2 style="font-family:'Syne',sans-serif;margin-bottom:16px;">⚡ Cheatsheet Streamlit</h2>

  <div class="table-wrap">
    <table>
      <tr><th>Função</th><th>Uso</th></tr>
      <tr><td><code>st.title()</code></td><td>Título principal (H1)</td></tr>
      <tr><td><code>st.header()</code></td><td>Cabeçalho (H2)</td></tr>
      <tr><td><code>st.write()</code></td><td>Texto + markdown + dados</td></tr>
      <tr><td><code>st.markdown()</code></td><td>Markdown completo</td></tr>
      <tr><td><code>st.code()</code></td><td>Bloco de código</td></tr>
      <tr><td><code>st.metric()</code></td><td>Card com número + delta</td></tr>
      <tr><td><code>st.divider()</code></td><td>Linha separadora</td></tr>
      <tr><td><code>st.spinner()</code></td><td>Loading animado</td></tr>
      <tr><td><code>st.success()</code></td><td>Alerta verde</td></tr>
      <tr><td><code>st.error()</code></td><td>Alerta vermelho</td></tr>
      <tr><td><code>st.warning()</code></td><td>Alerta amarelo</td></tr>
      <tr><td><code>st.info()</code></td><td>Alerta azul</td></tr>
    </table>
  </div>

  <div class="table-wrap" style="margin-top:20px">
    <table>
      <tr><th>Widget</th><th>Retorna</th></tr>
      <tr><td><code>st.text_input()</code></td><td>str</td></tr>
      <tr><td><code>st.number_input()</code></td><td>int/float</td></tr>
      <tr><td><code>st.slider()</code></td><td>int/float/tuple</td></tr>
      <tr><td><code>st.selectbox()</code></td><td>str (1 item)</td></tr>
      <tr><td><code>st.multiselect()</code></td><td>list</td></tr>
      <tr><td><code>st.checkbox()</code></td><td>bool</td></tr>
      <tr><td><code>st.radio()</code></td><td>str</td></tr>
      <tr><td><code>st.button()</code></td><td>bool (True 1x)</td></tr>
      <tr><td><code>st.file_uploader()</code></td><td>UploadedFile</td></tr>
      <tr><td><code>st.date_input()</code></td><td>date</td></tr>
    </table>
  </div>

  <div class="table-wrap" style="margin-top:20px">
    <table>
      <tr><th>Layout</th><th>Como usar</th></tr>
      <tr><td><code>st.columns(n)</code></td><td>c1,c2 = st.columns(2)</td></tr>
      <tr><td><code>st.tabs()</code></td><td>t1,t2 = st.tabs(["A","B"])</td></tr>
      <tr><td><code>st.sidebar</code></td><td>st.sidebar.write()</td></tr>
      <tr><td><code>st.expander()</code></td><td>with st.expander("+")</td></tr>
      <tr><td><code>st.container()</code></td><td>with st.container()</td></tr>
      <tr><td><code>st.empty()</code></td><td>placeholder atualizável</td></tr>
    </table>
  </div>

  <div class="section-title" style="margin-top:24px">🔑 Padrões Essenciais</div>
  <div class="code-block">
    <div class="code-header"><span class="code-lang">PYTHON</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
    <pre><span class="cm"># Cache de função</span>
<span class="nb">@st</span>.<span class="fn">cache_data</span>(ttl<span class="op">=</span><span class="nm">3600</span>)
<span class="kw">def</span> <span class="fn">carregar</span>(): ...

<span class="cm"># Session state</span>
<span class="kw">if</span> <span class="st">"x"</span> <span class="kw">not in</span> <span class="nb">st</span>.session_state:
    <span class="nb">st</span>.session_state.x <span class="op">=</span> <span class="nm">0</span>

<span class="cm"># Rerun forçado</span>
<span class="nb">st</span>.<span class="fn">rerun</span>()

<span class="cm"># Configuração da página (DEVE ser 1ª chamada)</span>
<span class="nb">st</span>.<span class="fn">set_page_config</span>(
    page_title<span class="op">=</span><span class="st">"App"</span>,
    layout<span class="op">=</span><span class="st">"wide"</span>,
    page_icon<span class="op">=</span><span class="st">"🚀"</span>
)</pre>
  </div>
</div>

<!-- ════════════════════════════════════
     PAINEL: PROJETOS
     ════════════════════════════════════ -->
<div id="panel-projetos" class="panel">
  <h2 style="font-family:'Syne',sans-serif;margin-bottom:8px;">🚀 Galeria de Projetos</h2>
  <p style="color:var(--muted);font-size:13px;margin-bottom:20px;">Projetos completos para praticar todos os conceitos</p>

  <div class="module-card" style="cursor:default;">
    <div class="module-header">
      <div class="module-num" style="background:linear-gradient(135deg,#10b981,#059669)">P1</div>
      <div class="module-info">
        <div class="module-title">🧮 Calculadora Científica</div>
        <div class="module-sub">Módulos 01-02 · Iniciante</div>
      </div>
    </div>
    <div class="module-body" style="display:block">
      <p style="font-size:13px">Operações básicas, trigonométricas e logarítmicas com histórico de cálculos usando session_state.</p>
      <div class="pill-row">
        <span class="pill">st.button</span><span class="pill">session_state</span><span class="pill">st.columns</span><span class="pill">math</span>
      </div>
    </div>
  </div>

  <div class="module-card" style="cursor:default;">
    <div class="module-header">
      <div class="module-num" style="background:linear-gradient(135deg,#f59e0b,#d97706)">P2</div>
      <div class="module-info">
        <div class="module-title">📈 Análise de Ações</div>
        <div class="module-sub">Módulos 03-04 · Intermediário</div>
      </div>
    </div>
    <div class="module-body" style="display:block">
      <p style="font-size:13px">Dashboard de ações com gráfico de candlestick, médias móveis e indicadores técnicos.</p>
      <div class="pill-row">
        <span class="pill">yfinance</span><span class="pill">plotly</span><span class="pill">pandas</span><span class="pill">st.cache_data</span>
      </div>
      <div class="code-block" style="margin-top:10px">
        <div class="code-header"><span class="code-lang">BASH · Instalar</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre>pip install yfinance plotly</pre>
      </div>
    </div>
  </div>

  <div class="module-card" style="cursor:default;">
    <div class="module-header">
      <div class="module-num" style="background:linear-gradient(135deg,#00d4ff,#0ea5e9)">P3</div>
      <div class="module-info">
        <div class="module-title">🌤️ App de Clima</div>
        <div class="module-sub">Módulo 06 · Intermediário</div>
      </div>
    </div>
    <div class="module-body" style="display:block">
      <p style="font-size:13px">Clima em tempo real usando a API gratuita Open-Meteo. Sem necessidade de chave API!</p>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON — clima.py</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>
<span class="kw">import</span> requests

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"🌤️ App de Clima"</span>)

cidades <span class="op">=</span> {
    <span class="st">"São Paulo"</span>: (-<span class="nm">23.55</span>, -<span class="nm">46.63</span>),
    <span class="st">"Rio de Janeiro"</span>: (-<span class="nm">22.90</span>, -<span class="nm">43.17</span>),
    <span class="st">"Belo Horizonte"</span>: (-<span class="nm">19.92</span>, -<span class="nm">43.94</span>),
    <span class="st">"Brasília"</span>: (-<span class="nm">15.78</span>, -<span class="nm">47.93</span>)
}

cidade <span class="op">=</span> <span class="nb">st</span>.<span class="fn">selectbox</span>(<span class="st">"Cidade"</span>, list(cidades.keys()))
lat, lon <span class="op">=</span> cidades[cidade]

url <span class="op">=</span> (
    <span class="st">f"https://api.open-meteo.com/v1/forecast?"</span>
    <span class="st">f"latitude={lat}&longitude={lon}"</span>
    <span class="st">f"&current=temperature_2m,weathercode"</span>
    <span class="st">f"&daily=temperature_2m_max,temperature_2m_min"</span>
    <span class="st">f"&timezone=America/Sao_Paulo&forecast_days=7"</span>
)

<span class="kw">with</span> <span class="nb">st</span>.<span class="fn">spinner</span>(<span class="st">"Carregando..."</span>):
    dados <span class="op">=</span> requests.<span class="fn">get</span>(url).<span class="fn">json</span>()

temp <span class="op">=</span> dados[<span class="st">"current"</span>][<span class="st">"temperature_2m"</span>]
<span class="nb">st</span>.<span class="fn">metric</span>(<span class="st">f"🌡️ {cidade} agora"</span>, <span class="st">f"{temp}°C"</span>)</pre>
      </div>
    </div>
  </div>

  <div class="module-card" style="cursor:default;">
    <div class="module-header">
      <div class="module-num" style="background:linear-gradient(135deg,#ff4b6e,#7c3aed)">P4</div>
      <div class="module-info">
        <div class="module-title">🤖 Chatbot com IA</div>
        <div class="module-sub">Módulo 07 · Avançado</div>
      </div>
    </div>
    <div class="module-body" style="display:block">
      <p style="font-size:13px">Interface de chat usando session_state para histórico + integração com API de IA.</p>
      <div class="termux-box">
        <div class="termux-title">📱 Instalar</div>
        <div class="code-block">
          <div class="code-header"><span class="code-lang">BASH</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
          <pre>pip install openai</pre>
        </div>
      </div>
      <div class="code-block">
        <div class="code-header"><span class="code-lang">PYTHON — chatbot.py</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
        <pre><span class="kw">import</span> streamlit <span class="kw">as</span> <span class="nb">st</span>

<span class="nb">st</span>.<span class="fn">title</span>(<span class="st">"💬 Chatbot"</span>)

<span class="kw">if</span> <span class="st">"msgs"</span> <span class="kw">not in</span> <span class="nb">st</span>.session_state:
    <span class="nb">st</span>.session_state.msgs <span class="op">=</span> []

<span class="cm"># Exibir histórico</span>
<span class="kw">for</span> m <span class="kw">in</span> <span class="nb">st</span>.session_state.msgs:
    <span class="kw">with</span> <span class="nb">st</span>.<span class="fn">chat_message</span>(m[<span class="st">"role"</span>]):
        <span class="nb">st</span>.<span class="fn">write</span>(m[<span class="st">"content"</span>])

<span class="cm"># Input do usuário</span>
<span class="kw">if</span> prompt <span class="op">:=</span> <span class="nb">st</span>.<span class="fn">chat_input</span>(<span class="st">"Mensagem..."</span>):
    <span class="nb">st</span>.session_state.msgs.<span class="fn">append</span>(
        {<span class="st">"role"</span>: <span class="st">"user"</span>, <span class="st">"content"</span>: prompt}
    )
    <span class="kw">with</span> <span class="nb">st</span>.<span class="fn">chat_message</span>(<span class="st">"user"</span>):
        <span class="nb">st</span>.<span class="fn">write</span>(prompt)
    
    <span class="cm"># Resposta simples (sem IA externa)</span>
    resposta <span class="op">=</span> <span class="st">f"Você disse: {prompt}"</span>
    <span class="nb">st</span>.session_state.msgs.<span class="fn">append</span>(
        {<span class="st">"role"</span>: <span class="st">"assistant"</span>, <span class="st">"content"</span>: resposta}
    )
    <span class="kw">with</span> <span class="nb">st</span>.<span class="fn">chat_message</span>(<span class="st">"assistant"</span>):
        <span class="nb">st</span>.<span class="fn">write</span>(resposta)</pre>
      </div>
    </div>
  </div>
</div>

<!-- ════════════════════════════════════
     PAINEL: TERMUX
     ════════════════════════════════════ -->
<div id="panel-termux" class="panel">
  <h2 style="font-family:'Syne',sans-serif;margin-bottom:8px;">📱 Guia Completo Termux</h2>
  <p style="color:var(--muted);font-size:13px;margin-bottom:20px;">Tudo que você precisa para programar no celular</p>

  <div class="termux-box">
    <div class="termux-title">🔧 Setup Inicial Completo</div>
    <div class="code-block">
      <div class="code-header"><span class="code-lang">BASH — Execute estes comandos primeiro</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
      <pre><span class="cm"># Atualizar tudo</span>
pkg update && pkg upgrade -y

<span class="cm"># Python + ferramentas</span>
pkg install python git nano -y

<span class="cm"># Pip atualizado</span>
pip install --upgrade pip

<span class="cm"># Streamlit + libs essenciais</span>
pip install streamlit pandas numpy matplotlib plotly requests

<span class="cm"># Verificar</span>
python --version
streamlit --version</pre>
    </div>
  </div>

  <div class="termux-box">
    <div class="termux-title">📝 Editor de Código no Termux</div>
    <div class="code-block">
      <div class="code-header"><span class="code-lang">BASH</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
      <pre><span class="cm"># Opção 1: nano (mais simples)</span>
nano app.py
<span class="cm"># Ctrl+S salvar · Ctrl+X sair</span>

<span class="cm"># Opção 2: vim (avançado)</span>
pkg install vim -y
vim app.py
<span class="cm"># :wq para salvar e sair</span>

<span class="cm"># Opção 3: usar editor externo</span>
<span class="cm"># Instale "Acode" ou "AIDE" na Play Store</span>
<span class="cm"># Edite os arquivos em ~/meu_app/</span></pre>
    </div>
  </div>

  <div class="termux-box">
    <div class="termux-title">⚡ Comandos Mais Usados</div>
    <div class="code-block">
      <div class="code-header"><span class="code-lang">BASH</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
      <pre><span class="cm"># Rodar app</span>
streamlit run app.py

<span class="cm"># Porta específica</span>
streamlit run app.py --server.port 8502

<span class="cm"># Sem abertura automática do browser</span>
streamlit run app.py --server.headless true

<span class="cm"># Ver processos rodando</span>
ps aux | grep streamlit

<span class="cm"># Matar processo</span>
pkill -f streamlit

<span class="cm"># Listar arquivos</span>
ls -la

<span class="cm"># Criar pasta de projeto</span>
mkdir ~/projetos && cd ~/projetos</pre>
    </div>
  </div>

  <div class="callout callout-tip">
    <span class="callout-icon">💡 Dica Pro</span>
    Abra o navegador e acesse <strong>http://localhost:8501</strong>. Mantenha tanto o Termux quanto o navegador abertos. Use "dividir tela" do Android para ver os dois ao mesmo tempo!
  </div>

  <div class="callout callout-warn">
    <span class="callout-icon">⚠️ Problema: ModuleNotFoundError</span>
    Se aparecer erro de módulo: <code>pip install nome_do_modulo</code><br>
    Ex: <code>pip install pandas plotly streamlit</code>
  </div>

  <div class="callout callout-warn">
    <span class="callout-icon">⚠️ Problema: Porta em uso</span>
    Execute: <code>streamlit run app.py --server.port 8502</code><br>
    Depois acesse: <strong>localhost:8502</strong>
  </div>

  <div class="termux-box">
    <div class="termux-title">🗂️ Estrutura de Pastas Recomendada</div>
    <div class="code-block">
      <div class="code-header"><span class="code-lang">BASH</span><button class="copy-btn" onclick="copyCode(this)">copiar</button></div>
      <pre><span class="cm"># Criar estrutura de projeto</span>
mkdir -p ~/streamlit_curso/{modulo01,modulo02,modulo03,projetos}
cd ~/streamlit_curso

<span class="cm"># Criar arquivo de aula</span>
nano modulo01/aula01_texto.py

<span class="cm"># Rodar aula</span>
streamlit run modulo01/aula01_texto.py</pre>
    </div>
  </div>

  <div class="progress-wrap">
    <div class="progress-label">
      <span>Progresso do Curso</span>
      <span id="prog-pct">0%</span>
    </div>
    <div class="progress-bar">
      <div class="progress-fill" id="prog-bar" style="width:0%"></div>
    </div>
  </div>

  <div style="display:flex;flex-wrap:wrap;gap:10px;margin-top:16px">
    <button onclick="updateProgress(12)" style="flex:1;min-width:100px;padding:10px;background:var(--surface2);border:1px solid var(--border);color:var(--text);border-radius:8px;cursor:pointer;font-size:13px;">✅ Módulo 00</button>
    <button onclick="updateProgress(25)" style="flex:1;min-width:100px;padding:10px;background:var(--surface2);border:1px solid var(--border);color:var(--text);border-radius:8px;cursor:pointer;font-size:13px;">✅ Módulo 01</button>
    <button onclick="updateProgress(37)" style="flex:1;min-width:100px;padding:10px;background:var(--surface2);border:1px solid var(--border);color:var(--text);border-radius:8px;cursor:pointer;font-size:13px;">✅ Módulo 02</button>
    <button onclick="updateProgress(50)" style="flex:1;min-width:100px;padding:10px;background:var(--surface2);border:1px solid var(--border);color:var(--text);border-radius:8px;cursor:pointer;font-size:13px;">✅ Módulo 03</button>
    <button onclick="updateProgress(62)" style="flex:1;min-width:100px;padding:10px;background:var(--surface2);border:1px solid var(--border);color:var(--text);border-radius:8px;cursor:pointer;font-size:13px;">✅ Módulo 04</button>
    <button onclick="updateProgress(75)" style="flex:1;min-width:100px;padding:10px;background:var(--surface2);border:1px solid var(--border);color:var(--text);border-radius:8px;cursor:pointer;font-size:13px;">✅ Módulo 05</button>
    <button onclick="updateProgress(87)" style="flex:1;min-width:100px;padding:10px;background:var(--surface2);border:1px solid var(--border);color:var(--text);border-radius:8px;cursor:pointer;font-size:13px;">✅ Módulo 06</button>
    <button onclick="updateProgress(100)" style="flex:1;min-width:100px;padding:10px;background:var(--accent);border:none;color:white;border-radius:8px;cursor:pointer;font-size:13px;font-weight:600;">🏆 Concluído!</button>
  </div>
</div>

<!-- SCROLL TO TOP -->
<div class="scroll-top" id="scrollTop" onclick="window.scrollTo({top:0,behavior:'smooth'})">↑</div>

<footer>
  <strong style="color:var(--accent)">Streamlit Academy</strong> · Curso completo para Termux/Mobile<br>
  <span style="font-size:11px">Do Zero ao Avançado · 8 Módulos · 40+ Exercícios</span>
</footer>

<script>
  function showPanel(id) {
    document.querySelectorAll('.panel').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
    document.getElementById('panel-' + id).classList.add('active');
    event.target.classList.add('active');
    window.scrollTo({top: 0, behavior: 'smooth'});
  }

  function toggleModule(card) {
    card.classList.toggle('open');
  }

  function copyCode(btn) {
    const pre = btn.closest('.code-block').querySelector('pre');
    const text = pre.innerText;
    navigator.clipboard.writeText(text).then(() => {
      btn.textContent = '✓ copiado';
      setTimeout(() => btn.textContent = 'copiar', 2000);
    }).catch(() => {
      btn.textContent = 'erro';
    });
  }

  function updateProgress(pct) {
    document.getElementById('prog-bar').style.width = pct + '%';
    document.getElementById('prog-pct').textContent = pct + '%';
  }

  // Scroll to top button
  window.addEventListener('scroll', () => {
    const btn = document.getElementById('scrollTop');
    if (window.scrollY > 300) btn.classList.add('visible');
    else btn.classList.remove('visible');
  });

  // Auto-open first module
  document.querySelector('.module-card').classList.add('open');
</script>
</body>
</html>

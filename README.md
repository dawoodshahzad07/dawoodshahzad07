<style>
  @import url('https://fonts.googleapis.com/css2?family=Geist+Mono:wght@400;500&family=Geist:wght@400;500;600&family=Instrument+Serif:ital@0;1&display=swap');

  .premium-portfolio-body {
    font-family: 'Geist Sans', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    background-color: #FBFBFA;
    color: #2F3437;
    line-height: 1.6;
    max-width: 56rem; /* max-w-4xl */
    margin: 0 auto;
    padding: 6rem 2rem; /* py-24 px-8 equivalent */
  }

  .editorial-serif {
    font-family: 'Instrument Serif', Georgia, serif;
    font-style: italic;
    letter-spacing: -0.03em;
    line-height: 1.1;
    color: #111111;
  }

  .mono-meta {
    font-family: 'Geist Mono', monospace;
    font-size: 0.8125rem;
    color: #787774;
    letter-spacing: -0.01em;
  }

  .divider-line {
    border: 0;
    border-top: 1px solid #EAEAEA;
    margin: 4rem 0;
  }

  .bento-grid {
    display: grid;
    grid-template-columns: repeat(12, minmax(0, 1fr));
    gap: 1.5rem;
    margin-top: 2.5rem;
  }

  .bento-card {
    background: #FFFFFF;
    border: 1px solid #EAEAEA;
    border-radius: 8px;
    padding: 2rem;
    transition: box-shadow 200ms cubic-bezier(0.16, 1, 0.3, 1);
  }

  .bento-card:hover {
    box-shadow: 0 2px 8px rgba(0,0,0,0.03);
  }

  .col-span-7 { grid-column: span 7 / span 7; }
  .col-span-5 { grid-column: span 5 / span 5; }
  .col-span-12 { grid-column: span 12 / span 12; }

  /* Muted Pastel Token Classes */
  .badge-tag {
    display: inline-flex;
    align-items: center;
    border-radius: 9999px;
    font-size: 0.6875rem;
    font-weight: 500;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    padding: 0.25rem 0.625rem;
  }

  .badge-blue { background-color: #E1F3FE; color: #1F6C9F; }
  .badge-green { background-color: #EDF3EC; color: #346538; }
  .badge-yellow { background-color: #FBF3DB; color: #956400; }

  /* Utility Interactive Components */
  .action-btn {
    display: inline-flex;
    align-items: center;
    background-color: #111111;
    color: #FFFFFF;
    font-size: 0.875rem;
    font-weight: 500;
    border-radius: 6px;
    padding: 0.625rem 1rem;
    text-decoration: none;
    transition: background-color 200ms ease;
  }

  .action-btn:hover { background-color: #333333; }
  .action-btn:active { transform: scale(0.98); }

  .social-link-icon {
    color: #787774;
    text-decoration: none;
    transition: color 150ms ease;
  }
  
  .social-link-icon:hover { color: #111111; }

  @media (max-width: 768px) {
    .col-span-7, .col-span-5, .col-span-12 { grid-column: span 12 / span 12; }
    .premium-portfolio-body { padding: 4rem 1.25rem; }
  }
</style>

<div class="premium-portfolio-body">

  <header style="display: flex; justify-content: space-between; align-items: flex-start; gap: 2rem;">
    <div>
      <span class="mono-meta">ARCHIVAL RECORD — ID: 0707</span>
      <h1 class="editorial-serif" style="font-size: 3.5rem; margin-top: 0.5rem; margin-bottom: 0.25rem;">Dawood Shahzad</h1>
      <p style="font-size: 1.125rem; color: #111111; font-weight: 500; margin: 0;">AI Systems & Intelligent Agent Engineer</p>
    </div>
    <div style="margin-top: 1rem;">
      <img src="https://komarev.com/ghpvc/?username=dawoodshahzad07&label=Views&color=111111&style=flat-square" alt="Metrics tracking frame" style="border: 1px solid #EAEAEA; border-radius: 4px;" />
    </div>
  </header>

  <hr class="divider-line" />

  <section class="bento-grid">
    
    <div class="bento-card col-span-7">
      <div style="display: flex; gap: 0.5rem; margin-bottom: 1rem;">
        <span class="badge-tag badge-blue">Active Research</span>
        <span class="badge-tag badge-green">Core Architecture</span>
      </div>
      <h2 style="font-size: 1.25rem; font-weight: 500; color: #111111; margin-bottom: 0.5rem;">Core Systems Focus</h2>
      <p style="color: #787774; font-size: 0.9375rem; margin: 0;">
        Specializing deeply in architectural automations and Agentic AI framework implementations. Developing autonomous execution pipelines that translate complex structural requirements into highly reliable production infrastructure.
      </p>
    </div>

    <div class="bento-card col-span-5">
      <span class="badge-tag badge-yellow" style="margin-bottom: 1rem;">Expertise</span>
      <h2 style="font-size: 1.25rem; font-weight: 500; color: #111111; margin-bottom: 0.5rem;">Domain Coverage</h2>
      <p style="color: #787774; font-size: 0.9375rem; margin: 0;">
        Available for deployment architectures covering stateful conversational chatbots, complex multi-agent system execution loops, and custom backend network engineering.
      </p>
    </div>

    <div class="bento-card col-span-12" style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 1.5rem;">
      <div>
        <h3 style="font-size: 1rem; font-weight: 500; color: #111111; margin-bottom: 0.25rem;">Inquiries & Communications</h3>
        <p class="mono-meta" style="margin: 0;">dawoodshahzad0707@gmail.com</p>
      </div>
      <div style="display: flex; align-items: center; gap: 1.5rem;">
        <a href="https://linkedin.com/in/dawood-shahzad-130508187" target="_blank" rel="noopener noreferrer" class="social-link-icon" title="LinkedIn Profile">
          <svg width="20" height="20" viewBox="0 0 256 256" fill="currentColor"><path d="M216,24H40A16,16,0,0,0,24,40V216a16,16,0,0,0,16,16H216a16,16,0,0,0,16-16V40A16,16,0,0,0,216,24Zm0,192H40V40H216V216ZM96,112v80a8,8,0,0,1-16,0V112a8,8,0,0,1,16,0Zm-8-32a12,12,0,1,1,12-12A12,12,0,0,1,88,80Zm112,64v48a8,8,0,0,1-16,0V144a24,24,0,0,0-48,0v48a8,8,0,0,1-16,0V112a8,8,0,0,1,15.79-1.78A40,40,0,0,1,200,144Z"/></svg>
        </a>
        <a href="https://twitter.com/" target="_blank" rel="noopener noreferrer" class="social-link-icon" title="X Network Profile">
          <svg width="20" height="20" viewBox="0 0 256 256" fill="currentColor"><path d="M214.1,24.16a16,16,0,0,0-15.35-.5L36.42,104.9a16,16,0,0,0,1,28.27L93.12,152a8,8,0,0,0,7.23-.32l91.64-55a8,8,0,0,1,8.26,13.76l-67.6,56.33a8,8,0,0,0-2.42,4.61l-18.06,60.2A16,16,0,0,0,127.46,232c.5,0,1,0,1.5-.07a16,16,0,0,0,13.62-11.83l74.1-222.29A16,16,0,0,0,214.1,24.16Z"/></svg>
        </a>
        <a href="https://github.com/dawoodshahzad07" target="_blank" rel="noopener noreferrer" class="social-link-icon" title="GitHub Codebase Profile">
          <svg width="20" height="20" viewBox="0 0 256 256" fill="currentColor"><path d="M208,104a48,48,0,0,0-10.43-29.74,4,4,0,0,1-.17-4.14,48,48,0,0,0-2-45.64,4,4,0,0,1,3.43-5.63c2.15-.12,6-.13,11-.07a55.12,55.12,0,0,1,34.78,14.65,4,4,0,0,1,.78,4.52A71.39,71.39,0,0,1,240,71.22c-.12,1.15-.36,2.37-.73,3.64A4,4,0,0,1,235.34,78,48,48,0,0,0,208,104Zm-41,12a4,4,0,0,0-4,4c0,22.06-21.53,40-48,40S67,142.06,67,120a4,4,0,0,0-4-4,48,48,0,0,0-27.34-26A4,4,0,0,1,32.33,85.6c-.37-1.27-.61-2.49-.73-3.64A71.39,71.39,0,0,1,35.53,39.3a4,4,0,0,1,.78-4.52A55.12,55.12,0,0,1,71.09,20.13c5-.06,8.83-.05,11,.07a4,4,0,0,1,3.43,5.63,48,48,0,0,0-2,45.64,4,4,0,0,1-.17,4.14A48,48,0,0,0,73,104,4,4,0,0,0,69,108c0,26,21,47.23,48,48V128H104a8,8,0,0,1,0-16h13V96a8,8,0,0,1,16,0v16h13a8,8,0,0,1,0,16H133v28c27-.77,48-22,48-48A4,4,0,0,0,167,116Z"/></svg>
        </a>
      </div>
    </div>

  </section>

  <hr class="divider-line" />

  <footer style="text-align: center;">
    <span class="mono-meta" style="display: block; margin-bottom: 0.75rem;">ENTERPRISE OPERATIONAL PORTAL</span>
    <a target="_blank" rel="noopener noreferrer" href="https://github.com/dawoodkodensoft" class="action-btn">
      <span>Access Dawood Kodensoft Portfolio</span>
      <svg width="14" height="14" viewBox="0 0 256 256" fill="currentColor" style="margin-left: 0.5rem;"><path d="M224,104a8,8,0,0,1-16,0V59.31l-98.34,98.35a8,8,0,0,1-11.32-11.32L196.69,48H152a8,8,0,0,1,0-16h64a8,8,0,0,1,8,8Zm-40,24a8,8,0,0,0-8,8v80H48V48h80a8,8,0,0,0,0-16H48A16,16,0,0,0,32,48V216a16,16,0,0,0,16,16H176a16,16,0,0,0,16-16V136A8,8,0,0,0,184,128Z"/></svg>
    </a>
  </footer>

</div>

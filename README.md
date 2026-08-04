# jacksondriley.github.io
Personal Website for People to Use :)
<!DOCTYPE html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title>Jackson Riley</title>

  <!-- SEO + link-preview text. << EDIT >> the og:url once you have a domain. -->
  <meta name="description" content="Jackson Riley — Information Systems Security student at Mount Mercy University, sprinter, and maker of things. Works with Java, Python, and Power BI." />
  <meta property="og:title" content="Jackson Riley" />
  <meta property="og:description" content="Information Systems Security student at Mount Mercy University, sprinter, and maker of things." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://yourdomain.com/" />
  <meta name="twitter:card" content="summary" />

  <!-- Emoji favicon (no image file needed). << EDIT >> the emoji if you like -->
  <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>👋</text></svg>" />

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,340;9..144,500;9..144,600&family=Newsreader:opsz,wght@6..72,400;6..72,500&display=swap" rel="stylesheet" />

  <style>
    :root {
      --paper:    #f6f4ef;
      --ink:      #211f1b;
      --muted:    #6b675e;
      --accent:   #3a4b8a;
      --accent-2: #4a5fb0;
      --hairline: #e2dfd7;
    }

    * { box-sizing: border-box; }

    html { -webkit-text-size-adjust: 100%; }

    body {
      margin: 0;
      background: var(--paper);
      color: var(--ink);
      font-family: "Newsreader", Georgia, "Times New Roman", serif;
      font-size: 1.25rem;
      line-height: 1.65;
      font-optical-sizing: auto;
      -webkit-font-smoothing: antialiased;
      text-rendering: optimizeLegibility;
      display: flex;
      min-height: 100vh;
      justify-content: center;
    }

    main {
      width: 100%;
      max-width: 40rem;
      padding: clamp(2.5rem, 8vw, 6rem) 1.5rem 3rem;
    }

    .eyebrow {
      font-family: "Newsreader", serif;
      font-size: 0.95rem;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: var(--muted);
      margin: 0 0 1.25rem;
    }

    h1 {
      font-family: "Fraunces", Georgia, serif;
      font-weight: 500;
      font-size: clamp(2.4rem, 7vw, 3.6rem);
      line-height: 1.08;
      letter-spacing: -0.015em;
      margin: 0 0 2rem;
      text-wrap: balance;
    }

    h1 em {
      font-style: italic;
      font-weight: 340;
    }

    p {
      margin: 0 0 1.5rem;
      max-width: 34rem;
    }

    .signoff {
      color: var(--muted);
      font-style: italic;
    }

    /* Signature element: offset indigo underline that thickens on hover */
    a {
      color: var(--accent);
      text-decoration: none;
      background-image: linear-gradient(var(--accent), var(--accent));
      background-size: 100% 1px;
      background-repeat: no-repeat;
      background-position: 0 1.15em;
      padding-bottom: 0.06em;
      transition: background-size 0.18s ease, color 0.18s ease;
    }

    a:hover,
    a:focus-visible {
      color: var(--accent-2);
      background-size: 100% 2px;
    }

    a:focus-visible {
      outline: 2px solid var(--accent);
      outline-offset: 3px;
      border-radius: 2px;
    }

    .socials {
      display: flex;
      gap: 1.1rem;
      align-items: center;
      margin-top: 3rem;
      padding-top: 2rem;
      border-top: 1px solid var(--hairline);
    }

    .socials a {
      background-image: none;
      padding: 0;
      line-height: 0;
      color: var(--muted);
      transition: color 0.18s ease, transform 0.18s ease;
    }

    .socials a:hover,
    .socials a:focus-visible {
      color: var(--ink);
      transform: translateY(-2px);
    }

    .socials svg { width: 24px; height: 24px; }

    footer {
      margin-top: 2.5rem;
      font-size: 0.9rem;
      color: var(--muted);
    }

    /* Gentle load-in, one line at a time */
    .reveal {
      opacity: 0;
      transform: translateY(10px);
      animation: rise 0.7s cubic-bezier(0.2, 0.65, 0.3, 1) forwards;
    }
    .reveal:nth-child(1) { animation-delay: 0.05s; }
    .reveal:nth-child(2) { animation-delay: 0.16s; }
    .reveal:nth-child(3) { animation-delay: 0.27s; }
    .reveal:nth-child(4) { animation-delay: 0.38s; }
    .reveal:nth-child(5) { animation-delay: 0.49s; }
    .reveal:nth-child(6) { animation-delay: 0.60s; }
    .reveal:nth-child(7) { animation-delay: 0.71s; }
    .reveal:nth-child(8) { animation-delay: 0.82s; }

    @keyframes rise {
      to { opacity: 1; transform: none; }
    }

    @media (prefers-reduced-motion: reduce) {
      .reveal { animation: none; opacity: 1; transform: none; }
      a { transition: none; }
    }
  </style>
</head>

<body>
  <main>
    <p class="eyebrow reveal">Greetings</p>

    <h1 class="reveal">My name's <em>Jackson Riley.</em></h1>

    <p class="reveal">
      I'm a maker of things and a problem solver. Right now I'm a student at
      Mount Mercy University, where I study Information Systems Security and
      run as a short sprinter for the Track &amp; Field team.
    </p>

    <p class="reveal">
      Along the way I've picked up a handful of technologies — Java, Python,
      and Power BI, to name just a few.
    </p>

    <p class="reveal">
      You can find me around as <strong>@jacksondriley</strong>. Say hello on
      <a href="https://www.linkedin.com/in/jackson-riley-517917355/" title="Jackson Riley on LinkedIn">LinkedIn</a>
      or take a look at what I'm building on
      <a href="https://github.com/jacksondriley" title="Jackson Riley on GitHub">GitHub</a> —
      both are linked below.
    </p>

    <p class="signoff reveal">Thanks for stopping by!</p>

    <nav class="socials reveal" aria-label="Social links">
      <a href="https://github.com/jacksondriley" title="GitHub" aria-label="GitHub">
        <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
          <path d="M12 .5C5.37.5 0 5.87 0 12.5c0 5.3 3.44 9.8 8.21 11.39.6.11.82-.26.82-.58 0-.29-.01-1.04-.02-2.05-3.34.73-4.04-1.61-4.04-1.61-.55-1.39-1.33-1.76-1.33-1.76-1.09-.75.08-.73.08-.73 1.2.09 1.84 1.24 1.84 1.24 1.07 1.83 2.81 1.3 3.5.99.11-.78.42-1.3.76-1.6-2.67-.3-5.47-1.34-5.47-5.95 0-1.31.47-2.39 1.24-3.23-.13-.3-.54-1.53.11-3.19 0 0 1.01-.32 3.3 1.23a11.5 11.5 0 0 1 3-.41c1.02 0 2.05.14 3 .41 2.29-1.55 3.3-1.23 3.3-1.23.65 1.66.24 2.89.12 3.19.77.84 1.23 1.92 1.23 3.23 0 4.62-2.8 5.64-5.48 5.94.43.37.81 1.1.81 2.22 0 1.6-.01 2.9-.01 3.29 0 .32.21.7.83.58A12 12 0 0 0 24 12.5C24 5.87 18.63.5 12 .5Z"/>
        </svg>
      </a>
      <a href="https://www.linkedin.com/in/jackson-riley-517917355/" title="LinkedIn" aria-label="LinkedIn">
        <svg viewBox="0 0 24 24" fill="currentColor" aria-hidden="true">
          <path d="M20.45 20.45h-3.56v-5.57c0-1.33-.03-3.04-1.85-3.04-1.85 0-2.14 1.45-2.14 2.94v5.67H9.35V9h3.42v1.56h.05c.48-.9 1.64-1.85 3.37-1.85 3.6 0 4.27 2.37 4.27 5.46v6.28ZM5.34 7.43a2.07 2.07 0 1 1 0-4.14 2.07 2.07 0 0 1 0 4.14ZM7.12 20.45H3.55V9h3.57v11.45ZM22.22 0H1.77C.79 0 0 .77 0 1.73v20.54C0 23.23.79 24 1.77 24h20.45c.98 0 1.78-.77 1.78-1.73V1.73C24 .77 23.2 0 22.22 0Z"/>
        </svg>
      </a>
    </nav>

    <footer class="reveal">
      © <span id="year"></span> Jackson Riley
    </footer>
  </main>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>

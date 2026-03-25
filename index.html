<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IV Corners</title>
    <link href="https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }

        :root {
            --bg: #0a0a0a;
            --bg-alt: #111111;
            --text: #e8e8e8;
            --text-muted: #777777;
            --text-dim: #444444;
            --border: #222222;
            --mono: 'Space Mono', monospace;
            --sans: 'DM Sans', -apple-system, BlinkMacSystemFont, sans-serif;
        }

        html { scroll-behavior: smooth; }

        body {
            background: var(--bg);
            color: var(--text);
            font-family: var(--sans);
            line-height: 1.6;
            font-size: 15px;
            font-weight: 300;
            overflow-x: hidden;
        }

        /* ─── NAV ─── */
        header { position: fixed; top: 0; left: 0; right: 0; z-index: 1000; padding: 0 2rem; }
        nav { display: flex; justify-content: space-between; align-items: center; padding: 1.5rem 0; }
        .logo { font-family: var(--sans); font-size: 32px; font-weight: 500; letter-spacing: -0.02em; text-decoration: none; color: var(--text); line-height: 1; }
        .nav-links { display: flex; list-style: none; gap: 0; align-items: center; }
        .nav-links a { display: flex; align-items: center; gap: 0.4rem; text-decoration: none; color: var(--text); font-family: var(--mono); font-size: 11px; letter-spacing: 0.12em; text-transform: uppercase; padding: 0.5rem 1.5rem; transition: opacity 0.3s; }
        .nav-links a::before { content: '\25CB'; font-size: 7px; opacity: 0.6; }
        .nav-links a:hover { opacity: 0.5; }
        .nav-toggle { display: none; background: none; border: 1px solid var(--text); font-family: var(--mono); font-size: 10px; cursor: pointer; color: var(--text); padding: 0.5rem 1rem; letter-spacing: 0.15em; text-transform: uppercase; }

        @media (max-width: 768px) {
            header { padding: 0 1.2rem; }
            .nav-links { display: none; position: fixed; top: 0; left: 0; right: 0; bottom: 0; flex-direction: column; background: var(--bg); padding: 6rem 2rem; gap: 0; z-index: 999; }
            .nav-links.active { display: flex; }
            .nav-links a { font-size: 14px; padding: 1.2rem 0; border-bottom: 1px solid var(--border); }
            .nav-toggle { display: block; z-index: 1001; }
        }

        /* ─── HERO ─── */
        .hero { position: relative; width: 100%; height: 100vh; display: flex; align-items: center; justify-content: center; overflow: hidden; }
        .hero-bg { position: absolute; inset: 0; background: #161616; }
        .hero-bg::after { content: ''; position: absolute; inset: 0; background: linear-gradient(180deg, rgba(10,10,10,0.3) 0%, rgba(10,10,10,0.05) 40%, rgba(10,10,10,0.05) 60%, rgba(10,10,10,0.5) 100%); }
        .hero-center-text { position: relative; z-index: 2; text-align: center; font-family: var(--mono); font-size: 12px; letter-spacing: 0.25em; text-transform: uppercase; color: var(--text); opacity: 0.85; }
        .hero-bottom { position: absolute; bottom: 1.5rem; left: 2rem; z-index: 2; font-family: var(--mono); font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--text); opacity: 0.6; line-height: 1.9; }
        .hero-pause { position: absolute; bottom: 1.5rem; right: 2rem; z-index: 2; font-family: var(--mono); font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--text); opacity: 0.6; background: none; border: 1px solid rgba(255,255,255,0.25); padding: 0.4rem 1rem; cursor: pointer; transition: opacity 0.3s; display: flex; align-items: center; gap: 0.5rem; }
        .hero-pause:hover { opacity: 1; }

        /* ─── COMMON ─── */
        section { padding: 6rem 3rem; max-width: 1400px; margin: 0 auto; }
        .section-label { font-family: var(--mono); font-size: 10px; letter-spacing: 0.2em; text-transform: uppercase; color: var(--text-dim); margin-bottom: 2rem; display: flex; align-items: center; gap: 1rem; }
        .section-label::after { content: ''; flex: 1; height: 1px; background: var(--border); }
        section h2 { font-family: var(--sans); font-size: 42px; font-weight: 300; letter-spacing: -0.03em; margin-bottom: 1rem; line-height: 1.15; }
        section p.subtitle { color: var(--text-muted); font-size: 15px; max-width: 600px; line-height: 1.8; margin-bottom: 3rem; }
        .divider { height: 1px; background: var(--border); margin: 3rem 0; }
        .btn { display: inline-flex; align-items: center; gap: 0.6rem; padding: 0.7rem 1.6rem; border: 1px solid var(--text); color: var(--text); text-decoration: none; font-family: var(--mono); font-size: 10px; letter-spacing: 0.15em; text-transform: uppercase; transition: all 0.3s; cursor: pointer; background: transparent; }
        .btn:hover { background: var(--text); color: var(--bg); }
        .btn-ghost { border-color: var(--border); color: var(--text-muted); }
        .btn-ghost:hover { border-color: var(--text); color: var(--text); background: transparent; }

        /* ─── EXPLANATION ─── */
        .explanation { border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); padding: 4rem 3rem; }
        .explanation-inner { max-width: 1400px; margin: 0 auto; display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; }
        .explanation-inner p { font-size: 14px; line-height: 1.9; color: var(--text-muted); }
        @media (max-width: 768px) { .explanation-inner { grid-template-columns: 1fr; gap: 1.5rem; } }

        /* ─── FEATURED ─── */
        .featured { border: 1px solid var(--border); overflow: hidden; margin-bottom: 4rem; transition: border-color 0.3s; }
        .featured:hover { border-color: #333; }
        .featured-image { width: 100%; height: 500px; background: #161616; display: flex; align-items: center; justify-content: center; font-family: var(--mono); color: var(--text-dim); font-size: 10px; text-transform: uppercase; letter-spacing: 0.15em; }
        .featured-content { padding: 2.5rem 3rem; border-top: 1px solid var(--border); display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 1.5rem; }
        .featured-info h3 { font-family: var(--sans); font-size: 22px; font-weight: 400; margin-bottom: 0.3rem; }
        .featured-meta { font-family: var(--mono); font-size: 10px; color: var(--text-dim); text-transform: uppercase; letter-spacing: 0.15em; }

        /* ─── SEARCH / FILTER BAR ─── */
        .archive-controls {
            display: flex;
            gap: 1px;
            background: var(--border);
            border: 1px solid var(--border);
            margin-bottom: 2.5rem;
        }
        .archive-search {
            flex: 1;
            padding: 1rem 1.5rem;
            background: var(--bg);
            border: none;
            color: var(--text);
            font-family: var(--sans);
            font-size: 14px;
            font-weight: 300;
            outline: none;
        }
        .archive-search::placeholder { color: var(--text-dim); }
        .filter-btn {
            padding: 1rem 1.5rem;
            background: var(--bg);
            border: none;
            color: var(--text-muted);
            font-family: var(--mono);
            font-size: 10px;
            letter-spacing: 0.12em;
            text-transform: uppercase;
            cursor: pointer;
            transition: all 0.3s;
            white-space: nowrap;
        }
        .filter-btn:hover, .filter-btn.active { color: var(--text); background: var(--bg-alt); }

        @media (max-width: 768px) {
            .archive-controls { flex-wrap: wrap; }
            .archive-search { min-width: 100%; }
        }

        /* ─── ARCHIVE ENTRY (unified artist + space) ─── */
        .archive-entry {
            border: 1px solid var(--border);
            margin-bottom: 2rem;
            transition: border-color 0.3s;
        }
        .archive-entry:hover { border-color: #333; }
        .archive-entry.hidden { display: none; }

        .entry-header {
            display: grid;
            grid-template-columns: 1fr 1fr;
        }
        @media (max-width: 900px) { .entry-header { grid-template-columns: 1fr; } }

        .entry-image {
            background: #161616;
            min-height: 340px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: var(--mono);
            color: var(--text-dim);
            font-size: 10px;
            text-transform: uppercase;
            letter-spacing: 0.15em;
        }

        .entry-body {
            padding: 3rem;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .entry-episode {
            font-family: var(--mono);
            font-size: 10px;
            color: var(--text-dim);
            letter-spacing: 0.15em;
            text-transform: uppercase;
            margin-bottom: 0.8rem;
        }

        .entry-body h3 {
            font-family: var(--sans);
            font-size: 22px;
            font-weight: 400;
            margin-bottom: 0.2rem;
        }

        .entry-body h3 span {
            color: var(--text-dim);
            font-weight: 300;
        }

        .entry-meta {
            font-family: var(--mono);
            font-size: 10px;
            color: var(--text-dim);
            text-transform: uppercase;
            letter-spacing: 0.12em;
            margin-bottom: 1.2rem;
        }

        .entry-body > p {
            color: var(--text-muted);
            font-size: 14px;
            line-height: 1.8;
            margin-bottom: 1.5rem;
        }

        .space-tags { margin-bottom: 1rem; }
        .space-tag {
            display: inline-block;
            font-family: var(--mono);
            font-size: 9px;
            letter-spacing: 0.12em;
            text-transform: uppercase;
            color: var(--text-muted);
            border: 1px solid var(--border);
            padding: 0.25rem 0.6rem;
            margin-right: 0.4rem;
            margin-bottom: 0.4rem;
        }

        /* ─── POLAROIDS ─── */
        .polaroids {
            display: flex;
            gap: 1rem;
            margin-top: 1.5rem;
            padding-top: 1.5rem;
            border-top: 1px solid var(--border);
        }
        .polaroid {
            flex: 1;
            background: #f0ece4;
            padding: 6px 6px 22px 6px;
            box-shadow: 1px 2px 8px rgba(0,0,0,0.35);
            transform: rotate(-1deg);
            transition: transform 0.3s;
        }
        .polaroid:nth-child(2) { transform: rotate(1.5deg); }
        .polaroid:nth-child(3) { transform: rotate(-0.5deg); }
        .polaroid:hover { transform: rotate(0deg) scale(1.03); z-index: 2; }
        .polaroid-img {
            width: 100%;
            aspect-ratio: 1;
            background: #ccc;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: var(--mono);
            font-size: 8px;
            color: #999;
            text-transform: uppercase;
            letter-spacing: 0.1em;
        }
        @media (max-width: 600px) {
            .polaroids { gap: 0.5rem; }
            .polaroid { padding: 4px 4px 16px 4px; }
        }

        .entry-links {
            display: flex;
            gap: 1.2rem;
            flex-wrap: wrap;
            margin-top: 1.5rem;
        }
        .entry-links a {
            font-family: var(--mono);
            font-size: 9px;
            color: var(--text-muted);
            text-decoration: none;
            text-transform: uppercase;
            letter-spacing: 0.12em;
            padding-bottom: 2px;
            border-bottom: 1px solid var(--border);
            transition: all 0.3s;
        }
        .entry-links a:hover { color: var(--text); border-color: var(--text); }


        /* ─── SUPPORT ─── */
        .support-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1px;
            background: var(--border);
            border: 1px solid var(--border);
            margin-top: 3rem;
        }
        @media (max-width: 900px) { .support-grid { grid-template-columns: 1fr; } }
        .support-item { background: var(--bg); padding: 3rem 2.5rem; }
        .support-num { font-family: var(--mono); font-size: 10px; color: var(--text-dim); letter-spacing: 0.15em; margin-bottom: 1.5rem; }
        .support-item h3 { font-family: var(--sans); font-size: 18px; font-weight: 400; margin-bottom: 0.8rem; }
        .support-item p { color: var(--text-muted); font-size: 13px; line-height: 1.8; }

        /* ─── ABOUT ─── */
        .about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; margin-top: 3rem; }
        .about-grid h3 { font-family: var(--mono); font-size: 10px; letter-spacing: 0.2em; text-transform: uppercase; color: var(--text-dim); margin-bottom: 1rem; }
        .about-grid p { color: var(--text-muted); font-size: 14px; line-height: 1.9; }
        @media (max-width: 768px) { .about-grid { grid-template-columns: 1fr; gap: 2rem; } }

        /* ─── CTA BANNER ─── */
        .cta-banner { border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); padding: 5rem 3rem; text-align: center; }
        .cta-banner h2 { font-family: var(--sans); font-size: 36px; font-weight: 300; letter-spacing: -0.02em; margin-bottom: 0.8rem; }
        .cta-banner p { color: var(--text-muted); font-size: 14px; margin-bottom: 2rem; }

        /* ─── FORM ─── */
        form { max-width: 600px; margin-top: 2rem; }
        .form-group { margin-bottom: 1.8rem; }
        label { display: block; font-family: var(--mono); font-size: 10px; letter-spacing: 0.15em; text-transform: uppercase; color: var(--text-dim); margin-bottom: 0.6rem; }
        input, textarea, select { width: 100%; padding: 0.9rem 0; border: none; border-bottom: 1px solid var(--border); background: transparent; color: var(--text); font-family: var(--sans); font-size: 14px; font-weight: 300; transition: border-color 0.3s; border-radius: 0; -webkit-appearance: none; }
        input:focus, textarea:focus, select:focus { outline: none; border-bottom-color: var(--text); }
        textarea { resize: vertical; min-height: 100px; }
        select { cursor: pointer; }
        select option { background: var(--bg); color: var(--text); }
        .contact-info { font-family: var(--mono); font-size: 10px; color: var(--text-dim); letter-spacing: 0.1em; text-transform: uppercase; margin-top: 3rem; line-height: 2.2; }

        /* ─── FOOTER ─── */
        footer { border-top: 1px solid var(--border); padding: 3rem; }
        .footer-content { max-width: 1400px; margin: 0 auto; display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; gap: 3rem; }
        .footer-section h3 { font-family: var(--mono); font-size: 10px; letter-spacing: 0.15em; text-transform: uppercase; color: var(--text-dim); margin-bottom: 1.2rem; }
        .footer-links { list-style: none; }
        .footer-links li { margin-bottom: 0.6rem; }
        .footer-links a { color: var(--text-muted); text-decoration: none; font-size: 13px; transition: color 0.3s; }
        .footer-links a:hover { color: var(--text); }
        .footer-section p { font-size: 13px; color: var(--text-muted); line-height: 1.7; max-width: 300px; }
        .social-row { display: flex; gap: 0.8rem; margin-top: 1rem; }
        .social-row a { display: inline-flex; align-items: center; justify-content: center; width: 30px; height: 30px; border: 1px solid var(--border); color: var(--text-muted); text-decoration: none; font-family: var(--mono); font-size: 10px; transition: all 0.3s; }
        .social-row a:hover { border-color: var(--text); color: var(--text); }
        .footer-bottom { width: 100%; border-top: 1px solid var(--border); padding-top: 2rem; margin-top: 1rem; display: flex; justify-content: space-between; align-items: center; }
        .footer-bottom p { font-family: var(--mono); font-size: 10px; color: var(--text-dim); letter-spacing: 0.1em; text-transform: uppercase; }

        /* ─── RESPONSIVE ─── */
        @media (max-width: 768px) {
            section { padding: 4rem 1.5rem; }
            .explanation { padding: 3rem 1.5rem; }
            section h2 { font-size: 30px; }
            .featured-image { height: 300px; }
            .featured-content { padding: 2rem; flex-direction: column; align-items: flex-start; }
            .cta-banner { padding: 4rem 1.5rem; }
            .cta-banner h2 { font-size: 26px; }
            .vote-section { padding: 4rem 1.5rem; }
            footer { padding: 2rem 1.5rem; }
            .hero-bottom { left: 1.2rem; bottom: 1.2rem; }
            .hero-pause { right: 1.2rem; bottom: 1.2rem; }
            .entry-body { padding: 2rem; }
        }

        /* ─── ANIMATION ─── */
        @keyframes fadeUp { from { opacity: 0; transform: translateY(12px); } to { opacity: 1; transform: translateY(0); } }
        .fade-in { animation: fadeUp 0.6s ease forwards; }
        .fade-in-1 { animation-delay: 0.1s; opacity: 0; }
        .fade-in-2 { animation-delay: 0.2s; opacity: 0; }
        .fade-in-3 { animation-delay: 0.3s; opacity: 0; }
        .fade-in-4 { animation-delay: 0.4s; opacity: 0; }
    </style>
</head>
<body>

    <!-- NAV -->
    <header>
        <nav>
            <a href="/" class="logo">IV Corners</a>
            <ul class="nav-links" id="navLinks">
                <li><a href="#archive">Archive</a></li>
                <li><a href="#support">Support</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Connect</a></li>
            </ul>
            <button class="nav-toggle" id="navToggle">Menu</button>
        </nav>
    </header>

    <!-- HERO -->
    <section class="hero">
        <div class="hero-bg"></div>
        <div class="hero-center-text fade-in fade-in-2">Music &middot; Spaces &middot; Community</div>
        <div class="hero-bottom fade-in fade-in-3">
            <div id="liveClock"></div>
            <div>San Francisco, CA</div>
            <div>&copy;2026 IV Corners</div>
        </div>
        <button class="hero-pause fade-in fade-in-4">&#10074;&#10074; &nbsp;Pause</button>
    </section>

    <!-- EXPLANATION -->
    <div class="explanation">
        <div class="explanation-inner fade-in fade-in-2">
            <p>IV Corners captures live music in San Francisco's most beautiful and overlooked spaces. Every week, a new performance filmed in a location worth knowing about &mdash; from hidden parks and backyard studios to landmark galleries and neighborhood institutions.</p>
            <p>More than a music series: we spotlight the gems that make this city what it is, and give local artists a platform to be seen, heard, and supported. Once a month, the community votes on our socials to pick the featured artist. New video every Monday.</p>
        </div>
    </div>

    <!-- LATEST -->
    <section id="latest">
        <div class="section-label">This Week</div>
        <div class="featured">
            <div class="featured-image">Featured Video</div>
            <div class="featured-content">
                <div class="featured-info">
                    <h3>Artist Name <span style="color: var(--text-dim); font-weight: 300;">at</span> Space Name</h3>
                    <div class="featured-meta">Episode 01 &middot; Neighborhood &middot; Genre</div>
                </div>
                <a href="https://youtube.com" target="_blank" class="btn">Watch on YouTube &rarr;</a>
            </div>
        </div>
    </section>

    <!-- ARCHIVE (unified artist + space) -->
    <section id="archive">
        <div class="section-label">Archive</div>
        <h2>Every Session</h2>
        <p class="subtitle">One artist. One space. One week. Browse every session we've ever filmed &mdash; searchable by artist, location, neighborhood, or genre.</p>

        <!-- Search + Filters -->
        <div class="archive-controls">
            <input type="text" class="archive-search" id="archiveSearch" placeholder="Search artist, space, neighborhood, genre...">
            <button class="filter-btn active" data-filter="all">All</button>
            <button class="filter-btn" data-filter="hidden-gem">Hidden Gems</button>
            <button class="filter-btn" data-filter="landmark">Landmarks</button>
            <button class="filter-btn" data-filter="outdoors">Outdoors</button>
        </div>

        <!-- Entry 1 -->
        <div class="archive-entry" data-tags="hidden-gem outdoors" data-search="artist name one folk mission district sutro baths">
            <div class="entry-header">
                <div class="entry-image">Session Photo</div>
                <div class="entry-body">
                    <div class="entry-episode">Episode 03</div>
                    <h3>Artist Name <span>at</span> Space Name</h3>
                    <div class="entry-meta">Mission District &middot; Folk &middot; March 2026</div>
                    <div class="space-tags">
                        <span class="space-tag">Hidden Gem</span>
                        <span class="space-tag">Outdoors</span>
                    </div>
                    <p>A short write-up about the session &mdash; the artist, the space, and the moment we captured. What made this pairing special.</p>
                    <div class="polaroids">
                        <div class="polaroid"><div class="polaroid-img">Photo 1</div></div>
                        <div class="polaroid"><div class="polaroid-img">Photo 2</div></div>
                        <div class="polaroid"><div class="polaroid-img">Photo 3</div></div>
                    </div>
                    <div class="entry-links">
                        <a href="#">Watch the Session</a>
                        <a href="#">Artist Spotify</a>
                        <a href="#">Artist Instagram</a>
                        <a href="#">Visit the Space</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Entry 2 -->
        <div class="archive-entry" data-tags="landmark gallery" data-search="artist name two jazz soma gallery space">
            <div class="entry-header">
                <div class="entry-image">Session Photo</div>
                <div class="entry-body">
                    <div class="entry-episode">Episode 02</div>
                    <h3>Artist Name <span>at</span> Space Name</h3>
                    <div class="entry-meta">SoMa &middot; Jazz &middot; March 2026</div>
                    <div class="space-tags">
                        <span class="space-tag">Landmark</span>
                        <span class="space-tag">Gallery</span>
                    </div>
                    <p>A short write-up about the session &mdash; the artist, the space, and the moment we captured. What made this pairing special.</p>
                    <div class="polaroids">
                        <div class="polaroid"><div class="polaroid-img">Photo 1</div></div>
                        <div class="polaroid"><div class="polaroid-img">Photo 2</div></div>
                        <div class="polaroid"><div class="polaroid-img">Photo 3</div></div>
                    </div>
                    <div class="entry-links">
                        <a href="#">Watch the Session</a>
                        <a href="#">Artist Spotify</a>
                        <a href="#">Artist Instagram</a>
                        <a href="#">Visit the Space</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Entry 3 -->
        <div class="archive-entry" data-tags="hidden-gem outdoors" data-search="artist name three electronic sunset rooftop">
            <div class="entry-header">
                <div class="entry-image">Session Photo</div>
                <div class="entry-body">
                    <div class="entry-episode">Episode 01</div>
                    <h3>Artist Name <span>at</span> Space Name</h3>
                    <div class="entry-meta">Sunset &middot; Electronic &middot; February 2026</div>
                    <div class="space-tags">
                        <span class="space-tag">Hidden Gem</span>
                        <span class="space-tag">Outdoors</span>
                    </div>
                    <p>A short write-up about the session &mdash; the artist, the space, and the moment we captured. What made this pairing special.</p>
                    <div class="polaroids">
                        <div class="polaroid"><div class="polaroid-img">Photo 1</div></div>
                        <div class="polaroid"><div class="polaroid-img">Photo 2</div></div>
                        <div class="polaroid"><div class="polaroid-img">Photo 3</div></div>
                    </div>
                    <div class="entry-links">
                        <a href="#">Watch the Session</a>
                        <a href="#">Artist Spotify</a>
                        <a href="#">Artist Instagram</a>
                        <a href="#">Visit the Space</a>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <!-- SUPPORT -->
    <section id="support">
        <div class="section-label">Support Local</div>
        <h2>How We Give Back</h2>
        <p class="subtitle">IV Corners is built around a simple idea: the people and places that make a city special deserve to be celebrated and supported.</p>

        <div class="support-grid">
            <div class="support-item">
                <div class="support-num">01</div>
                <h3>Artist Platform</h3>
                <p>Every session is a free, professionally produced video for the artist. Full creative freedom, no strings. Their music, their way, shared with an audience that cares.</p>
            </div>
            <div class="support-item">
                <div class="support-num">02</div>
                <h3>Space Spotlight</h3>
                <p>We highlight the venues, parks, studios, and gathering places that give SF its character. Each space gets its own story, driving foot traffic and awareness to places that matter.</p>
            </div>
            <div class="support-item">
                <div class="support-num">03</div>
                <h3>Community First</h3>
                <p>No gatekeeping. We take submissions from anyone &mdash; suggest a location you love, an artist you think deserves shine, or a collaboration you want to see happen. This project belongs to the city.</p>
            </div>
        </div>
    </section>

    <!-- ABOUT -->
    <section id="about">
        <div class="section-label">About</div>
        <h2>IV Corners</h2>
        <p class="subtitle">A music and culture project documenting live performances in San Francisco's most beautiful and overlooked spaces &mdash; and the local artists who bring them to life.</p>

        <div class="divider"></div>

        <div class="about-grid">
            <div>
                <h3>The Format</h3>
                <p>One artist or collaboration. One location. Ten minutes of music. Two minutes of conversation. Filmed, edited, and released every Monday. Simple as that.</p>
            </div>
            <div>
                <h3>The Mission</h3>
                <p>Celebrate the people and places that make San Francisco feel like home. Give local artists a platform. Shine a light on spaces &mdash; hidden and iconic &mdash; that deserve to be experienced.</p>
            </div>
        </div>

        <div class="divider"></div>

        <div class="section-label">Creator</div>
        <p class="subtitle"><strong style="font-weight: 500; color: var(--text);">Noah Solt</strong> is a videographer documenting San Francisco's creative community. <a href="https://instagram.com/noahsolt" style="color: var(--text-muted); text-decoration: underline; text-underline-offset: 3px;" target="_blank">@noahsolt</a></p>
    </section>

    <!-- CTA BANNER -->
    <div class="cta-banner">
        <h2>Know a Gem? Know an Artist?</h2>
        <p>This project is shaped by the city. Tell us about a space worth filming in or an artist worth hearing.</p>
        <a href="#contact" class="btn">Get in Touch &rarr;</a>
    </div>

    <!-- CONTACT -->
    <section id="contact">
        <div class="section-label">Connect</div>
        <h2>Reach Out</h2>
        <p class="subtitle">Submit a location, suggest an artist, or just say hey.</p>

        <form id="contactForm">
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="inquiry">What's This About?</label>
                <select id="inquiry" name="inquiry" required>
                    <option value="">Select...</option>
                    <option value="location">Submit a Space / Location</option>
                    <option value="artist">Suggest an Artist</option>
                    <option value="collab">Collaboration / Partnership</option>
                    <option value="other">Something Else</option>
                </select>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" required></textarea>
            </div>
            <button type="submit" class="btn">Send &rarr;</button>
        </form>

        <div class="contact-info">
            <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="4a2925243e2b293e0a233c292538242f383964292527">[email&#160;protected]</a><br>
            @ivcorners on Instagram &amp; TikTok
        </div>
    </section>

    <!-- FOOTER -->
    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>IV Corners</h3>
                <p>Music, spaces, and community in San Francisco. Supporting local artists and spotlighting the gems that make this city worth it.</p>
                <div class="social-row">
                    <a href="https://instagram.com/ivcorners" target="_blank" title="Instagram">IG</a>
                    <a href="https://tiktok.com/@ivcorners" target="_blank" title="TikTok">TK</a>
                    <a href="https://youtube.com/@ivcorners" target="_blank" title="YouTube">YT</a>
                </div>
            </div>
            <div class="footer-section">
                <h3>Explore</h3>
                <ul class="footer-links">
                    <li><a href="#archive">Archive</a></li>
                    <li><a href="#support">Support</a></li>
                    <li><a href="#about">About</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>Connect</h3>
                <ul class="footer-links">
                    <li><a href="https://instagram.com/ivcorners" target="_blank">Instagram</a></li>
                    <li><a href="https://tiktok.com/@ivcorners" target="_blank">TikTok</a></li>
                    <li><a href="https://youtube.com/@ivcorners" target="_blank">YouTube</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
            <div class="footer-bottom">
                <p>&copy;2026 IV Corners</p>
                <p>San Francisco, CA</p>
            </div>
        </div>
    </footer>

    <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
        // ─── Nav toggle ───
        const navToggle = document.getElementById('navToggle');
        const navLinks = document.getElementById('navLinks');
        navToggle.addEventListener('click', () => {
            const isActive = navLinks.classList.toggle('active');
            navToggle.textContent = isActive ? 'Close' : 'Menu';
        });
        navLinks.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => { navLinks.classList.remove('active'); navToggle.textContent = 'Menu'; });
        });

        // ─── Contact form ───
        const contactForm = document.getElementById('contactForm');
        if (contactForm) {
            contactForm.addEventListener('submit', (e) => {
                e.preventDefault();
                alert('Thanks for reaching out! We\'ll be in touch.');
                contactForm.reset();
            });
        }

        // ─── Smooth scroll ───
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                const href = this.getAttribute('href');
                if (href !== '#' && document.querySelector(href)) {
                    e.preventDefault();
                    document.querySelector(href).scrollIntoView({ behavior: 'smooth' });
                }
            });
        });

        // ─── Live clock ───
        function updateClock() {
            const now = new Date();
            const h = now.getHours();
            const m = String(now.getMinutes()).padStart(2, '0');
            const s = String(now.getSeconds()).padStart(2, '0');
            const ampm = h >= 12 ? 'PM' : 'AM';
            const h12 = h % 12 || 12;
            const el = document.getElementById('liveClock');
            if (el) el.textContent = `${String(h12).padStart(2, '0')}:${m}:${s}${ampm}`;
        }
        updateClock();
        setInterval(updateClock, 1000);

        // ─── Archive search + filter ───
        const searchInput = document.getElementById('archiveSearch');
        const filterBtns = document.querySelectorAll('.filter-btn');
        const entries = document.querySelectorAll('.archive-entry');
        let activeFilter = 'all';

        function filterArchive() {
            const query = searchInput.value.toLowerCase().trim();
            entries.forEach(entry => {
                const tags = entry.dataset.tags || '';
                const searchText = entry.dataset.search || '';
                const matchesFilter = activeFilter === 'all' || tags.includes(activeFilter);
                const matchesSearch = !query || searchText.includes(query);
                entry.classList.toggle('hidden', !(matchesFilter && matchesSearch));
            });
        }

        searchInput.addEventListener('input', filterArchive);

        filterBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                filterBtns.forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                activeFilter = btn.dataset.filter;
                filterArchive();
            });
        });

    </script>

</body>
</html>

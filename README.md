# Nate Arens

**Ohio State University, graduating May 2027**  
I build real systems across product engineering, XR, AI, robotics, and data-heavy tooling.

In the last few years I have shipped a public Meta Quest game, built browser-based scientific tooling with a WASM runtime, wired LLMs into robotics and AR systems, and worked in production-oriented cloud and monitoring environments.

## Proof, Fast

| Area | Evidence |
| --- | --- |
| Shipped product | **Chromarun**: 1,150+ installs, 575+ lifetime active users, 40 levels, hand tracking, saves, leaderboards, custom levels |
| Scientific systems | **XPPAutHome**: XPPAUT web port with `.ode` upload, simulation, bifurcation tools, export, and WASM-first runtime |
| Robotics + AI | **Comet**: Unitree Go2 stack with Unity, Python, Gemini, Wit.ai, TCP, WebRTC, ngrok, and ~30 supported natural-language commands |
| XR + data | **ARChat**: Meta Quest 3 interface for QR-linked context, natural-language querying, and AR overlays; presented at NCUR 2025 |

## Watch / Play

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://www.youtube.com/watch?v=3sIsHlFQGgE">
        <img src="https://img.youtube.com/vi/3sIsHlFQGgE/hqdefault.jpg" alt="Chromarun trailer" width="100%" />
      </a>
      <br />
      <strong>Chromarun trailer</strong>
      <br />
      <a href="https://www.meta.com/experiences/chromarun/4405707952806774/">Meta listing</a> · <a href="https://www.youtube.com/watch?v=RLCw0jw2iWA&list=PLzLJrZy1zzpC5rQm2ozT7f3oe-LIgFPBc">All levels</a>
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://nate27624.github.io/BloomwaveGarden/">
        <img src="./assets/bloomwave-preview.png" alt="Bloomwave Garden screenshot" width="100%" />
      </a>
      <br />
      <strong>Bloomwave Garden web build</strong>
      <br />
      <a href="https://nate27624.github.io/BloomwaveGarden/">Play in browser</a> · <a href="https://github.com/Nate27624/BloomwaveGarden">Repo</a>
    </td>
  </tr>
</table>

## Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Nate27624/Chromarun">Chromarun</a></h3>
      <p>Founded <strong>Targy LLC</strong> and solely developed the shipped Meta Quest VR game.</p>
      <p><strong>Interesting system:</strong> raycast-driven procedural generation for an effectively unlimited, non-repeating VR obstacle course.</p>
      <p><strong>Other systems:</strong> 40 handcrafted levels, hand tracking, saves, leaderboards, and custom level creation.</p>
      <p><a href="https://github.com/Nate27624/Chromarun">Repo</a> · <a href="https://www.youtube.com/watch?v=3sIsHlFQGgE">Trailer</a> · <a href="https://www.meta.com/experiences/chromarun/4405707952806774/">Store page</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Nate27624/XPPAutHome">XPPAutHome</a></h3>
      <p>Web-first XPPAUT port for neuroscience and dynamical-systems workflows.</p>
      <p><strong>What it supports:</strong> model upload, simulation, phase-plane analysis, bifurcation views, and export to SVG, PNG, and CSV.</p>
      <p><strong>Interesting system:</strong> typed worker APIs with a WASM-first runtime and fallback execution path.</p>
      <p><a href="https://github.com/Nate27624/XPPAutHome">Repo</a> · <a href="https://nate27624.github.io/XPPAutHome/">Live demo</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Nate27624/robot-dog">Comet</a></h3>
      <p>LLM-driven robot dog prototype built around a <strong>Unitree Go2</strong>.</p>
      <p><strong>What it does:</strong> routes speech and visual context through a Unity client, controller, and Python server to execute predefined robot actions.</p>
      <p><strong>Interesting system:</strong> custom parser and command mapping for ~30 natural-language commands without pretending the model autonomously invents robot behavior.</p>
      <p><a href="https://github.com/Nate27624/robot-dog">Repo</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Nate27624/ARChat-showcase">ARChat</a></h3>
      <p><strong>Primary developer</strong> on an AR data-exploration system for Meta Quest 3.</p>
      <p><strong>What it does:</strong> loads QR-linked context, accepts natural-language questions, and returns spoken answers plus AR overlays tied to the scene.</p>
      <p><strong>Interesting system:</strong> Quest frontend + Python backend + DuckDB + Gemini + Wit.ai, including a scrcpy-based workaround before Meta exposed normal environment access.</p>
      <p><a href="https://github.com/Nate27624/ARChat-showcase">Case study</a> · <a href="https://drive.google.com/file/d/1zi6qT34vRLoi6KbfhmMs5f2yFb919Cdn/view?usp=sharing">In-app showcase</a> · <a href="https://drive.google.com/file/d/1B8bxKl5PCI7nh6CTLLRgHoKdsB_YiMlA/view?usp=sharing">NCUR presentation</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Nate27624/BloomwaveGarden">BloomwaveGarden</a></h3>
      <p>Current farming-game build across browser and native iOS paths.</p>
      <p><strong>What it includes:</strong> burst-based gameplay, progression, HUD systems, audio handling, leaderboards, and release-oriented marketing assets.</p>
      <p><strong>Interesting angle:</strong> a current product build that can bridge gameplay engineering with future analytics and experimentation work.</p>
      <p><a href="https://github.com/Nate27624/BloomwaveGarden">Repo</a> · <a href="https://nate27624.github.io/BloomwaveGarden/">Web build</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Nate27624/pawmaq.com">pawmaq.com</a></h3>
      <p>Open-source social platform workspace focused on privacy, moderation, and account integrity.</p>
      <p><strong>What it includes:</strong> anonymous passkey auth, media posting, moderation-first architecture, and feed UX.</p>
      <p><strong>Interesting angle:</strong> product-minded system design across auth, frontend flows, and operational constraints.</p>
      <p><a href="https://github.com/Nate27624/pawmaq.com">Repo</a></p>
    </td>
  </tr>
</table>

## Third-Party Signal

<a href="https://www.meta.com/experiences/chromarun/4405707952806774/">
  <img src="./assets/chromarun-review.png" alt="Chromarun five-star review from QUACKBIRTH on September 2, 2024" width="100%" />
</a>

> "The best game on Meta (no exaggeration)"

## Experience Snapshot

- **Nationwide, Software Engineering Intern:** work across AWS, EC2, Alation, New Relic, and CI/CD; built production/test monitoring and a Bash workflow that replaced manual external-drive backups with GitHub-backed automation.
- **Stealth startup, Software Developer:** sole iOS developer for a Ray-Ban Meta smart-glasses prototype using Apple Vision for on-device object detection and ruleset-driven capture readiness.
- **Teaching Assistant, College Algebra:** taught recitations and supported roughly 60 students per semester with strong instructor ratings.

## Selected Supporting Work

- [ProgrammingChallenge](https://github.com/Nate27624/ProgrammingChallenge): PyTorch speech emotion recognition work that adds applied ML depth.
- `financial-tracking` / Houston Finance: local-first personal-finance desktop app with encrypted storage, Plaid read-only boundaries, and release automation; currently private pending final privacy review.
- [ARChatDBs](https://github.com/Nate27624/ARChatDBs): supporting data assets for ARChat.

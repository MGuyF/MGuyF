<!--
  ==================================================================
  GitHub Profile README (responsive card) - Guy Fleury Manirakiza (Manguy) / MGuyF
  Proudly Burundian 🇧🇮 - country code +257 - Full-Stack Developer
  Portfolio: https://manguy-portfolio.vercel.app/
  This IS the live README.md of the MGuyF/MGuyF repository.
  ----------------------------------------------------------------
  WHY THE CARD IS STACKED (photo on top, panel below)
  GitHub strips <style>, style=, class= and data-* from READMEs, so there is
  NO media query and NO script. Only <table>/<td width>, <img width>,
  <details> and <picture> survive. GitHub's own stylesheet then does:
      .markdown-body table { width:max-content; max-width:100%;
                             display:block; overflow:auto }
      .markdown-body img   { max-width:100% }
      .markdown-body pre   { overflow:auto }  with white-space:pre
  The panel is white-space:pre, so it has an unshrinkable ~595px minimum
  width, and inside a table that minimum STARVED the 40% photo column of the
  old side-by-side card. Measured with headless Chrome on GitHub's real CSS:
      1280 / 1024 desktop -> photo 399x512 / 281x361 px    OK
       768 tablet         -> photo  25x32 px (collapsed)   BAD
      <=500 / 414 / 375 / 320 phone -> photo 0x0 px (GONE)  BAD
  Two columns can never fit a phone regardless: 399px photo + 595px panel is
  994px of minimum width versus ~343px usable on a 375px screen.
  Stacking removes the competing minimums. Re-measured after the change:
      1280 / 1024 / 768 / 414 / 375 / 320 -> photo 399x512 px at EVERY width,
      the page never scrolls sideways, and only the panel scrolls sideways,
      which is exactly how a normal GitHub code block behaves on a phone.
  The card stays a compact 621px centred card on desktop.
  ----------------------------------------------------------------
  SIZING THE PHOTO
  GitHub renders <pre> at 85% of 16px = 13.6px, line-height 19.72px, with
  16px vertical padding. The photo is 768x986 (ratio 1.2839) and width="399"
  gives 399x512px. Stacking means the photo no longer has to match the panel
  height; if you resize it keep the ratio:  width = panelHeight / 1.2839
  ----------------------------------------------------------------
  THREE GITHUB GOTCHAS (all handled below)
  1. GitHub strips inline style, so the inline CSS only drives local previews.
  2. A blank line inside <pre> closes the raw-HTML block on GitHub and the rest
     is rebuilt as <p>/<h2> at 16px (mixed font sizes). Never add one here.
  3. The photo is wrapped in an <a> so it becomes a 399px tap target on a
     phone and opens the portfolio. GitHub keeps that anchor as-is.
  ==================================================================
-->

<div align="center">
  <table border="0" cellspacing="0" cellpadding="0" style="border-collapse: collapse; border: none; background-color: #ffffff; width: 100%;">
    <tr>
      <td align="center" valign="middle" style="border: none;">
        <a href="https://manguy-portfolio.vercel.app/" title="Portfolio of Guy Fleury Manirakiza (Manguy), full-stack developer"><img src="assets/guy-fleury-manirakiza-manguy-full-stack-developer.webp" width="399" alt="Guy Fleury Manirakiza (Manguy) — Burundian full-stack web developer based in Nyamata, Rwanda · React, Next.js, TypeScript, Django, Laravel, PostgreSQL" title="Guy Fleury Manirakiza (Manguy) — full-stack web developer · manguy-portfolio.vercel.app" aria-label="Guy Fleury Manirakiza (Manguy) — Burundian full-stack web developer based in Nyamata, Rwanda · React, Next.js, TypeScript, Django, Laravel, PostgreSQL" style="width: 100%; max-width: 399px; height: auto; border-radius: 12px;" /></a>
      </td>
    </tr>
    <tr>
      <td style="border: none; text-align: left;"><pre style="font-family: monospace; font-size: 13.6px; line-height: 20px; color: #111827; background: transparent; border: none; margin: 0; padding: 16px 0; white-space: pre;">
<b>MGuyF@github</b> ----------------------------------------------
<b>. Name:</b> ................ Guy Fleury Manirakiza (Manguy)
<b>. Origin:</b> .............. Burundian 🇧🇮 · country code +257
<b>. Based in:</b> ............ Nyamata, Rwanda 📍 · remote / on-site
<b>. Role:</b> ................ Full-Stack Developer · open to work
<b>. Education:</b> ........... B.S. Software Engineering (ULT, Burundi)
<b>. Languages:</b> ........... TypeScript, JavaScript, Python, PHP, SQL
<b>. Front-end:</b> ........... React, Next.js, Vue, Inertia, Tailwind
<b>. Back-end:</b> ............ Django, DRF, Laravel, REST &amp; GraphQL
<b>. Data &amp; Maps:</b> ......... PostgreSQL, PostGIS, GeoDjango, MapLibre
<b>. Tools:</b> ............... Git, GitHub Actions, Vercel, Render
<b>. Portfolio:</b> ........... <a href="https://manguy-portfolio.vercel.app/" title="Portfolio of Guy Fleury Manirakiza (Manguy), full-stack developer" aria-label="Portfolio of Guy Fleury Manirakiza (Manguy), full-stack developer" style="color: #0284c7; text-decoration: none;">manguy-portfolio.vercel.app</a>
<b>. Email:</b> ............... <a href="mailto:2000291gf@gmail.com" title="Email Guy Fleury Manirakiza (Manguy)" aria-label="Email Guy Fleury Manirakiza (Manguy)" style="color: #0284c7; text-decoration: none;">2000291gf@gmail.com</a>
<b>. LinkedIn:</b> ............ <a href="https://www.linkedin.com/in/gfmanirakiza29-1-bdi/" title="LinkedIn profile of Guy Fleury Manirakiza (Manguy)" aria-label="LinkedIn profile of Guy Fleury Manirakiza (Manguy)" style="color: #0284c7; text-decoration: none;">linkedin.com/in/gfmanirakiza29-1-bdi</a>
<b>. GitHub:</b> .............. <a href="https://github.com/MGuyF" title="GitHub profile of MGuyF (Guy Fleury Manirakiza)" aria-label="GitHub profile of MGuyF (Guy Fleury Manirakiza)" style="color: #0284c7; text-decoration: none;">github.com/MGuyF</a>
<b>Featured Projects</b> -----------------------------------------
<b>. SOSGEOAID:</b> ........... <a href="https://sos-geo-aid.vercel.app/" title="SOSGEOAID — humanitarian aid geolocation platform by Manguy" aria-label="SOSGEOAID — humanitarian aid geolocation platform by Manguy" style="color: #0284c7; text-decoration: none;">Aid geolocation · Next.js + PostGIS</a>
<b>. RefuLearn:</b> ........... <a href="https://refulearn.vercel.app/" title="RefuLearn — refugee education platform by Manguy" aria-label="RefuLearn — refugee education platform by Manguy" style="color: #0284c7; text-decoration: none;">Refugee education platform</a> · <a href="https://github.com/MGuyF/RefuLearn" title="RefuLearn source code on GitHub" aria-label="RefuLearn source code on GitHub" style="color: #0284c7; text-decoration: none;">code</a>
<b>. Bus Driver:</b> .......... <a href="https://bus-driver-full-stack.vercel.app/" title="Bus Driver management app by Manguy" aria-label="Bus Driver management app by Manguy" style="color: #0284c7; text-decoration: none;">Drivers + tours admin</a> · <a href="https://github.com/MGuyF/Bus-Driver-FullStack" title="Bus Driver FullStack source code on GitHub" aria-label="Bus Driver FullStack source code on GitHub" style="color: #0284c7; text-decoration: none;">code</a>
<b>. Blog:</b> ................ <a href="https://blog-laravue-demo-dbx4.onrender.com/" title="Laravel + Vue mini-blog by Manguy" aria-label="Laravel + Vue mini-blog by Manguy" style="color: #0284c7; text-decoration: none;">Mini-blog · Laravel + Vue</a> · <a href="https://github.com/MGuyF/blog-laravue-demo" title="blog-laravue-demo source code on GitHub" aria-label="blog-laravue-demo source code on GitHub" style="color: #0284c7; text-decoration: none;">code</a>
<b>. User Mgmt:</b> ........... <a href="https://user-management-assessment-green.vercel.app/" title="User management app (React 19 + TypeScript) by Manguy" aria-label="User management app (React 19 + TypeScript) by Manguy" style="color: #0284c7; text-decoration: none;">React 19 + TS data table</a>
<b>. EBMS:</b> ................ <a href="https://github.com/MGuyF/odoo-obr-ebms-showcase" title="Odoo-OBR-EBMS to Burundi OBR eBM e-invoicing integration" aria-label="Odoo-OBR-EBMS to Burundi OBR eBM e-invoicing integration" style="color: #0284c7; text-decoration: none;">Odoo-OBR-EBMS (showcase)</a>
------------------------------------------------------------
        </pre></td>
    </tr>
  </table>
</div>

---

<div align="center">
  <sub>Built with passion by <b>Guy Fleury Manirakiza (Manguy)</b> · Amahoro from Burundi 🇧🇮</sub>
</div>

+++
title = "Startseite"
description = "die Zentrale"
[extra]
no_header = true
styles = ["home/style.css"]
[extra.links]
about_page = "/pages/ueber-mich/"
+++

<div class="container-fill">

<div>
{{ poloroid() }}

<div id="title">
ham3l.CLOUD
</div>

# 🌐 Hallo und willkommen in meinem digitalen Labor

Ein Ort, an dem ich **neue Ideen teste** und **digitale Lösungen entwickle**.  
Online kennt man mich als **`Ham3L`** _(Mein Nutzername auf verschiedenen Plattformen)_.

> 💡 Tipp: Bleib neugierig und probiere Neues aus!

---

✨ **Fun Fact:** Kleine Experimente führen oft zu den besten Lösungen!  
🔹 Tools, Tipps und Tricks findest du hier direkt in meinem digitalen Labor.

<div class="buttons start big">
  <a href="#ueber-mich-preview" class="suggested button scroll-to">Über mich ↓</a>
  <a href="#splash" class="suggested button scroll-to">Splash →</a>
</div>
</div>
</div>

---

## Über mich (Vorschau)

{% set about_page = get_page(path="pages/ueber-mich") %}

<div id="ueber-mich-preview">
  <!-- Vorschau: erste 250 Zeichen -->
  {{ about_page.content | truncate(250, "…") | safe }}

  <br><br>
  <!-- Echter interner Link für Zola -->
  <a href="{{ page.extra.links.about_page }}" class="suggested button">Mehr über mich →</a>
</div>

---

<ul class="masonry">

<!-- Card Start -->
<li>
<article>
**Seit vielen Jahren beschäftige ich mich mit digitalen Technologien,** derzeit konzentriere ich mich auf <abbr id="project" title="ein spezielles Entwicklungsprojekt">innovative Softwarelösungen</abbr>. Mein Ziel ist es, Prozesse zu optimieren und nachhaltige Ergebnisse zu erzielen.
</article>
</li>
<!-- Card End -->

<!-- Card Start -->
<li>
<article>
> "Wenn es sich lohnt, etwas zu bauen, lohnt es sich auch, es zu teilen. Echte Innovatoren stellen ihre Projekte online und lassen die Community daran wachsen."
> _~Ham3L_
</article>
</li>
<!-- Card End -->

</ul>

> [!NOTE]
> Noch in Arbeit!  
> Schau bald wieder vorbei für Updates und Einblicke aus meinem digitalen Labor.
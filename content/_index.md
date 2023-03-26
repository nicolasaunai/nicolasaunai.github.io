---
title: Nicolas Aunai
date: 2022-10-24
type: landing
headless: true
---

<style>
  .author-profile {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
  }

  .author-avatar {
    flex: 1;
    max-width: 200px;
  }

  .author-bio {
    flex: 3;
  }
</style>

<section id="about">
  <h2>Nicolas Aunai</h2>
  <div class="author-profile">
    <div class="author-avatar">
      {{ with .Site.Params.social }}
      <ul class="social-icons">
        {{ range . }}
        <li>
          <a href="{{ .link }}" title="{{ .label }}" target="_blank" rel="noopener">
            <i class="{{ .icon_pack }} fa-fw {{ .icon }}"></i>
          </a>
        </li>
        {{ end }}
      </ul>
      {{ end }}
      <p>Space Plasma Physicist</p>
      <p><a href="https://www.lpp.fr">Laboratory of Plasma Physics / CNRS</a></p>
    </div>
    <div class="author-bio">
      {{ with .Site.GetPage "page" "authors/_index.md" }}
      {{ .Content }}
      {{ end }}
    </div>
  </div>
</section>


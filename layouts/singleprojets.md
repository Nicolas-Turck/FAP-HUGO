+++
date = 2020-11-27T08:26:00Z
draft = true
title = "projets"

+++
{{ define "projets" }}
    <section class="section">
      <article>
        <div class="columns is-centered">
  <div class="column max-800px">
    <h1 class="title is-1">{{ .Title }}</h1>
    <div class="content">
      {{ .Content }}
    </div>
  </div>
</div>
      </article>
    </section>
    {{ end }}
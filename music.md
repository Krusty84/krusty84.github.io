---
layout: homepage
title: "Music"
permalink: /music.html
electronic_apple_music: https://music.apple.com/us/playlist/my-electronic-music/pl.u-DdAN8lPI0ZbDBeo
regular_apple_music: https://music.apple.com/us/playlist/my-favorite-songs/pl.u-76oNl2Mtv0ro82l
---

<div id="content-area" data-page-content>
  <div class="music-page">
    <section class="post-item">
      <h2 class="post-title">Electronic Music</h2>
      <p>More than 900 (3 days of non-stop music) tracks, you may download playlist or use my shared Apple Music playlist</p>
      <div class="post-links">
        <a href="{{ '/assets/files/music_electro_playlist.txt' | relative_url }}" class="post-link" download>[Download Playlist]</a>
        {% if page.electronic_apple_music %}
        <a href="{{ page.electronic_apple_music }}" class="post-link" target="_blank" rel="noopener">[Apple Music Playlist - updated frequently]</a>
        {% endif %}
      </div>
    </section>

    <section class="post-item">
      <h2 class="post-title">Musical Jam (From Serge Gainsbourg to NOFX)</h2>
      <p>More than 3000 tracks (9 days of non-stop music), you may download playlist or use my shared Apple Music playlist</p>
      <div class="post-links">
        <a href="{{ '/assets/files/music_general_playlist.txt' | relative_url }}" class="post-link" download>[Download Playlist]</a>
        {% if page.regular_apple_music %}
        <a href="{{ page.regular_apple_music }}" class="post-link" target="_blank" rel="noopener">[Apple Music Playlist - updated frequently]</a>
        {% endif %}
      </div>
    </section>

  </div>
</div>

<style>
  .music-page .post-item {
    margin-bottom: 3rem;
    padding-bottom: 2rem;
    border-bottom: 1px solid #eee;
    color: #000;
  }

  .music-page .post-item h2 {
    margin: 0 0 8px 0;
    font-size: 1.35rem;
  }

  .music-page .post-title {
    align-items: center;
    display: flex;
    gap: 8px;
  }

  .music-page .post-item small,
  .music-page .post-item p,
  .music-page .post-item a {
    color: #000;
  }

  .music-page .tag {
    background: #f0f0f0;
    color: #000;
    padding: 2px 8px;
    border-radius: 12px;
    font-size: 0.9rem;
  }

  .music-page .post-links {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
  }

  .music-page .post-link {
    color: #000;
    text-decoration: none;
  }

  .music-page .post-link:hover {
    text-decoration: underline;
  }

  @media (prefers-color-scheme: dark) {
    .music-page .post-item {
      border-color: #444;
    }
  }
</style>

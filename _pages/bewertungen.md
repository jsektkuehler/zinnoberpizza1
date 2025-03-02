---
layout: default
title: Bewertungen
permalink: /bewertungen/
---

<form action="https://formspree.io/f/mzzpvldr" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="rating">Bewertung (1-5):</label>
  <select id="rating" name="rating" required>
    <option value="1">1</option>
    <option value="2">2</option>
    <option value="3">3</option>
    <option value="4">4</option>
    <option value="5">5</option>
  </select>

  <label for="message">Kommentar:</label>
  <textarea id="message" name="message" required></textarea>

  <button type="submit">Abschicken</button>
</form>

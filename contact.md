---
layout: page
title: About us
subtitle: 
---

Fill out the form below to get in touch:

<!-- Form -->
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <br>
  <input type="text" id="name" name="name" required>
  <br><br>

  <label for="email">Email:</label>
  <br>
  <input type="email" id="email" name="email" required>
  <br><br>

  <label for="message">Message:</label>
  <br>
  <textarea id="message" name="message" rows="5" required></textarea>
  <br><br>

  <button type="submit">Submit</button>
</form>

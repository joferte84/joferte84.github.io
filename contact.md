---
layout: default
title: Contacto
---

<div align="center">
  <h1>Contacto</h1>
  <img src="{{ '/assets/images/jorge_fernandez.jpg' | relative_url }}" alt="Foto de Jorge Fernández" width="300" height="auto">
</div>

<div class="container">
  <h2>¿Interesado en colaborar o discutir un proyecto?</h2>
  <h2>¡Contáctame aquí!</h2>
  
  <form action="https://formspree.io/f/xvgpjdwv" method="POST">
    <label for="name">Nombre:</label><br>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="email">Correo electrónico:</label><br>
    <input type="email" id="email" name="_replyto" required><br><br>
    
    <label for="message">Mensaje:</label><br>
    <textarea id="message" name="message" rows="5" required></textarea><br><br>
    
    <button type="submit">Enviar</button>
  </form>
</div>

---

[Volver al inicio]({{ site.baseurl }}/index.html)

---
layout: default
title: Contacto
---

<div align="center">
  <h1>Contacto</h1>
  <img src="{{ '/assets/images/jorge_fernandez.jpg' | relative_url }}" alt="Foto de Jorge Fernández" width="300" height="auto">
</div>

<div class="container">
  <h2>Envíame un mensaje</h2>
  
  <form action="https://formspree.io/f/{your-form-id}" method="POST">
    <label for="name">Nombre:</label><br>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="email">Correo electrónico:</label><br>
    <input type="email" id="email" name="_replyto" required><br><br>
    
    <label for="message">Mensaje:</label><br>
    <textarea id="message" name="message" rows="5" required></textarea><br><br>
    
    <button type="submit">Enviar</button>
  </form>
</div>

# Otros medios de contacto

- [LinkedIn](https://www.linkedin.com/in/joferte)
- [GitHub](https://github.com/joferte84)
- Correo electrónico: [jorge_fernandez_84@yahoo.es](mailto:jorge_fernandez_84@yahoo.es)

---

[Volver al inicio]({{ site.baseurl }}/index.html)

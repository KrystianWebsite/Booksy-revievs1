---
title: "Kontakt"
description: "Formularz kontaktowy"
---

# Skontaktuj się z nami

Możesz napisać do nas, korzystając z formularza:

<form
  name="contact"
  method="POST"
  data-netlify="true"
  netlify-honeypot="bot-field"
>
  <input type="hidden" name="form-name" value="contact" />
  
  <!-- Pole honeypot (antyspam) -->
  <p style="display:none">
    <label>Nie wypełniaj: <input name="bot-field" /></label>
  </p>

  <p>
    <label>Imię: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Email: <input type="email" name="email" /></label>
  </p>

  <button type="submit">Wyślij</button>
</form>

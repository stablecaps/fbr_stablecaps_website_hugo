---
title: "Contact"
date: 2025-05-29
type: page
layout: page
---

{{< raw >}}

<form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
  <input type="hidden" name="form-name" value="contact" />
  <p hidden>
    <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
  </p>

  <p>
    <label>Your Name:<br />
    <input type="text" name="name" required></label>
  </p>

  <p>
    <label>Your Email:<br />
    <input type="email" name="email" required></label>
  </p>

  <p>
    <label>Your Message:<br />
    <textarea name="message" rows="5" required></textarea></label>
  </p>

  <p><button type="submit">Send</button></p>
</form>

{{< /raw >}}

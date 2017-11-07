---
title: Contact
header:
  overlay_image: "/assets/images/unsplash-image-1.jpg"
permalink: contactme
layout: single
---

<form id="contact-form" data-netlify="true" netlify-honeypot="bot-field">
	<p class="hidden">
		<label>Don’t fill this out: <input name="bot-field"></label>
	</p>
  <input class="form-field" name="name" id="name" type="text" placeholder="Your name">
    <input class="form-field" name="mail" id="mail" type="text" placeholder="Email">
    <textarea class="form-field" name="messageForm" id="messageForm" rows="1" placeholder="Your Message"></textarea>
    <input type="submit" id="submit-contact" class="btn-alt active shadow" type="submit" value="Send">
</form>
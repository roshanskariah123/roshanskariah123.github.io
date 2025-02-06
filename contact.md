---
layout: page
title: Contact Me
permalink: /contact/
---

<div style="text-align: center; margin-top: 20px;">
  <h1 style="font-size: 2.5em; font-weight: bold;">Get in Touch</h1>
  <p style="font-size: 1.2em; color: #555; margin-bottom: 40px;">
    I'd love to hear from you! Please fill out the form below to send me a message.
  </p>
</div>

<div style="max-width: 600px; margin: 0 auto; padding: 20px; background-color: #f9f9f9; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);">
  <form action="https://formspree.io/f/your-form-id" method="POST">
    <div style="margin-bottom: 15px;">
      <label for="name" style="font-size: 1em; font-weight: bold;">Your Name:</label><br>
      <input type="text" id="name" name="name" required style="width: 100%; padding: 10px; font-size: 1em; border: 1px solid #ccc; border-radius: 5px;">
    </div>

    <div style="margin-bottom: 15px;">
      <label for="email" style="font-size: 1em; font-weight: bold;">Your Email:</label><br>
      <input type="email" id="email" name="email" required style="width: 100%; padding: 10px; font-size: 1em; border: 1px solid #ccc; border-radius: 5px;">
    </div>

    <div style="margin-bottom: 15px;">
      <label for="topic" style="font-size: 1em; font-weight: bold;">Topic:</label><br>
      <input type="text" id="topic" name="topic" required style="width: 100%; padding: 10px; font-size: 1em; border: 1px solid #ccc; border-radius: 5px;">
    </div>

    <div style="margin-bottom: 15px;">
      <label for="message" style="font-size: 1em; font-weight: bold;">Your Message:</label><br>
      <textarea id="message" name="message" rows="5" required style="width: 100%; padding: 10px; font-size: 1em; border: 1px solid #ccc; border-radius: 5px;"></textarea>
    </div>

    <div style="text-align: center;">
      <button type="submit" style="background-color: #008AFF; color: white; padding: 10px 20px; font-size: 1em; font-weight: bold; border: none; border-radius: 5px; cursor: pointer;">
        Send Message
      </button>
    </div>
  </form>
</div>

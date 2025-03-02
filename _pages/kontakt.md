---
layout: default
title: Kontakt
permalink: /kontakt/
---

<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #f4f4f9;
  }

  h3 {
    color: #333;
    text-align: center;
  }

  form {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
  }

  label {
    display: block;
    margin-bottom: 10px;
    color: #555;
    font-weight: bold;
  }

  input[type="text"],
  input[type="email"],
  textarea {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 4px;
    font-size: 16px;
    box-sizing: border-box;
  }

  input[type="text"]:focus,
  input[type="email"]:focus,
  textarea:focus {
    border-color: #007bff;
    outline: none;
    box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
  }

  textarea {
    height: 150px;
    resize: vertical;
  }

  button[type="submit"] {
    background-color: #007bff;
    color: #fff;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
    width: 100%;
  }

  button[type="submit"]:hover {
    background-color: #0056b3;
  }

  @media (max-width: 600px) {
    form {
      padding: 15px;
    }

    button[type="submit"] {
      font-size: 14px;
    }
  }
</style>

### Kontaktieren Sie uns

<form action="https://formspree.io/f/mblrkvle" method="POST">
  <input type="hidden" name="_to" value="hallo@zinnoberpizza.com">
  
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" placeholder="Ihr Name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="_replyto" placeholder="Ihre E-Mail-Adresse" required>

  <label for="message">Nachricht:</label>
  <textarea id="message" name="message" placeholder="Ihre Nachricht" required></textarea>

  <button type="submit">Senden</button>
</form>

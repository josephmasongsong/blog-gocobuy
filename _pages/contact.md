---
layout: default
title: Contact Us
permalink: /contact
---

<p>
Interested in <a href="https://www.gocobuy.com">CoBuy</a>, have a question, or want to know more?  Shoot us an email. We’d love to hear from you.
</p>

<hr/>

<p>
Fields marked with an <span class="text-danger">*</span> are required
</p>

<form name="contact" method="POST" data-netlify="true">
  <p class="form-group">
    <label for="formName">Name <span class="text-danger">*</span></label>
    <input type="text" name="name" class="form-control" id="formName" required/>
  </p>
  <p class="form-group">
    <label form="formEmail">Email <span class="text-danger">*</span></label>
    <input type="email" name="email" class="form-control" id="formEmail" required/>
  </p>
  <p class="form-group">
    <label for="formPhone">Phone</label>
    <input type="phone" name="phone" class="form-control" id="formPhone"/>
  </p>
  <p  class="form-group">
    <label for="formMessage">Message <span class="text-danger">*</span></label>
    <textarea name="message" class="form-control" id="formMessage" required></textarea>
  </p>
  <p>
    <button type="submit" class="btn btn-primary">Send Message</button>
  </p>
</form>


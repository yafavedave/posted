---
layout: page
title: Contact
permalink: /contact/
---
<form name="contact" method="POST" data-netlify="true" class="page-form" accept-charset="UTF-8">
    <label for="InputEmail">Email</label>
    <input type="email" name="email" class="form-control" id="InputEmail" aria-describedby="emailHelp" placeholder="Enter email" required="required">
    <label for="InputName">Name</label>
    <input type="text" name="name" class="form-control" id="InputName" placeholder="Enter your name" required="required">
    <label for="InputMessage">Message</label>
    <textarea name="message" id="InputMessage" placeholder="Enter your message" required="required"></textarea>
    <button class="btn" type="submit">
        <span class="btn-label">Submit</span>
    </button>
</form>

---
layout: page
title: Contact
permalink: /contact/
---

### Contact

Feel free to contact us if you have any questions. We will try to respond as soon as possible.

<form action="https://getsimpleform.com/messages?form_api_token={{ site.simpleform_token }}" method="post">
    <input type="hidden" name="redirect_to" value="{{ site.url }}/sent/" />
    <div class="col-lg-6">
        <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control transparent" name="name" id="name" placeholder="Enter Name" value="" required>
        </div>
        <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control transparent" id="email" name="email" placeholder="Enter Email" value="" required>
        </div>
        <div class="form-group">
            <label for="message">Message</label>
            <textarea name="message" id="message" class="form-control transparent" rows="5" required></textarea>
        </div>
        <input type="submit" name="submit" id="submit" value="Submit" class="btn btn-info pull-right">
    </div>
</form>

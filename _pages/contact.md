---
layout: page
title: Contact Cocept
permalink: /contact/
published: true
---

## Contact Cocept

Interested in working together? You can get in touch using the form below. We usually respond within a couple of hours.

<form action="//formspree.io/max@cocept.io" method="POST" id="contact">
    <input type="hidden" name="_next" value="{{site.url}}/thanks" />
    <input type="text" name="_gotcha" style="display:none" />

	<div class="form-group">
        <label>Name</label>
        <input type="text" class="form-control" name="name" />
    </div>
    <div class="form-group">
        <label>Email address</label>
        <input type="text" class="form-control" name="email" />
    </div>
	<div class="form-group">
		<label>Message</label>
		<textarea name="message" class="form-control" rows="3"></textarea>
	</div>
	<div class="form-group">
		<input type="submit" value="Send" class="btn btn-primary">
	</div>
</form>

<script src="/js/contact.js"></script>
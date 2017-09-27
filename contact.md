---
title: Contact
layout: page
description: Form, Social Media, Email</br></br>romain[at]claret[dot]tech
image: contact.jpg
---

<section>
	<h4>Form</h4>
	<form id="contactform" method="POST">
		<div class="row uniform">
		<div class="6u 12u$(xsmall)">
				<input type="text" name="name" value="" placeholder="Name" />
			</div>
			<div class="6u$ 12u$(xsmall)">
				<input type="email" name="_replyto" value="" placeholder="Email" />
			</div>
			<div class="12u$">
				<textarea name="message" placeholder="Enter your message" rows="6"></textarea>
			</div>
			<div class="12u$">
				<ul class="actions">
					<li><input type="submit" value="Send Message" /></li>
				</ul>
			</div>
		</div>
		<input type="hidden" name="_subject" value="Contact from Claret.Tech" />
		<input type="hidden" name="_next" value="//claret.tech/" />
		<input type="text" name="_gotcha" style="display:none" />
	</form>
</section>

<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', 'https://formspree.io/' + 'romain' + '@' + 'claret' + '.' + 'tech');
</script>

---
title: "İletişim"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Lütfen mesajınızı {{site.name}} e gönderin. En kısa süre içerisinde geri dönmüş oluruz!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="İsim*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Adres*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Mesaj*" required></textarea>    
<input class="btn btn-success" type="submit" value="Gönder">
</form>

---
title:      Contact
subtitle:   Get in touch!
slug:       contact
menu:       3
---
<article class="bg-white border-bottom py-5">
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-sm-8">
        <h2 class="text-center mb-5">Drop Us a Line</h2>
        <p class="text-justify">Do you want to send Selena a fan mail? Do you have any film, interviews or other work enquiries? Or do you simply want to say hello to the webmasters behind the website? Drop us a line! We will forward your e-mail to the correct person if necessary and you will receive a reply within a week.</p>
      </div>
    </div>
    <div class="text-center">
      <a href="#contactform" class="btn-scroll">
        <i class="fa fa-angle-down animated"></i>
      </a>
    </div>
  </div>
</article>

<section id="contactform" class="py-5">
  <div class="container">
    <div class="row">

      <div class="col-sm-3 order-sm-last">
        <h5>E-mail address</h5>
        <p>selena.li.official [@] gmail.com</p>
        <hr>
        <h5>Social media</h5>
        <label>Selena's accounts</label>
        {% include social-media.liquid %}
        <label>Fanclub accounts</label>
        {% include social-media.liquid account="fanclub" %}
      </div>

      <div class="col-sm-9 order-sm-first">
        <form method="POST" action="//formspree.io/mrgzdvdy" role="form">
          <div class="form-group row">
            <label for="name" class="col-sm-2 col-form-label">Your Name</label>
            <div class="col-sm-10">
              <input type="text" id="name" name="name" class="form-control">
            </div>
          </div>

          <div class="form-group row">
            <label for="email" class="col-sm-2 col-form-label">Your Email</label>
            <div class="col-sm-10">
              <input type="email" id="email" name="_replyto" class="form-control">
            </div>
          </div>

          <div class="form-group row">
            <label for="category" class="col-sm-2 col-form-label">Type of message</label>
            <div class="col-sm-10">
              <select id="category" name="category" class="form-control">
                <option>Fan mail</option>
                <option>Work</option>
                <option>Website</option>
                <option>Others</option>
              </select>
            </div>
          </div>

          <div class="form-group row">
            <label for="subject" class="col-sm-2 col-form-label">Subject</label>
            <div class="col-sm-10">
              <input type="text" id="subject" name="subject" class="form-control">
            </div>
          </div>

          <div class="form-group row">
            <label for="message" class="col-sm-2 col-form-label">Your Message</label>
            <div class="col-sm-10">
              <textarea id="message" name="message" class="form-control" rows="15"></textarea>
            </div>
          </div>

          <div class="form-group row">
            <div class="col-sm-10 offset-sm-2">
              <button type="submit" class="btn btn-primary">Send message</button>
            </div>
          </div>
        </form>
      </div>

    </div>
  </div>
</section>
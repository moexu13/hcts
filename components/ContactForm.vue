<template>
  <section class="form-container">
    <h2 class="section__title">Contact Us</h2>

    <div class="contact-form" id="contact-form">
      <form action="/" method="post">
        <div class="form-group">
          <label for="name" class="form-label">Name</label>
          <input id="name" type="text" name="name" class="form-control" />
        </div>

        <div class="form-group">
          <label for="email" class="form-label">Email</label>
          <input id="email" type="email" name="email" class="form-control" />
        </div>

        <div class="form-group">
          <label for="phone" class="form-label">Phone</label>
          <input id="phone" type="tel" name="phone" class="form-control" />
        </div>

        <div class="form-group">
          <label for="message" class="form-label">Message</label>
          <textarea
            id="message"
            name="message"
            class="form-control"
            rows="6"
            cols="50"
          ></textarea>
        </div>

        <div class="row btn-container">
          <button class="btn btn-submit">Send</button>
        </div>
      </form>
    </div>
  </section>
</template>

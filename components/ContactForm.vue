<template>
  <section class="form-container">
    <div class="tagline__container">
      <div class="tagline">Contact Us</div>
    </div>
    <div class="contact-form" id="contact-form">
      <form action="/" method="post">
        <p>
          <label for="name" class="label">Name</label><br />
          <input id="name" type="text" name="name" class="textbox" />
        </p>

        <p>
          <label for="email" class="label">Email</label><br />
          <input id="email" type="email" name="email" class="textbox" />
        </p>

        <p>
          <label for="phone" class="label">Phone</label><br />
          <input id="phone" type="tel" name="phone" class="textbox" />
        </p>

        <p>
          <label for="message" class="label">Message</label><br />
          <textarea
            id="message"
            name="message"
            class="message"
            rows="6"
            cols="50"
          ></textarea>
        </p>

        <p class="btn-container">
          <button class="btn btn-submit">Send</button>
        </p>
      </form>
    </div>
  </section>
</template>

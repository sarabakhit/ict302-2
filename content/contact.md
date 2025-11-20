+++
title: "Contact"
+++

<section class="contact-page">

## Contact Us

Have a question about parking, permits, or reservations?  
Fill out the form below and our team will get back to you shortly.

<form name="parking-contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
  <input type="hidden" name="form-name" value="parking-contact" />

  <p class="hidden">
    <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
  </p>

  <p>
    <label>Your Name:<br />
      <input type="text" name="name" required>
    </label>
  </p>

  <p>
    <label>Your Email:<br />
      <input type="email" name="email" required>
    </label>
  </p>

  <p>
    <label>License Plate Number (optional):<br />
      <input type="text" name="plate">
    </label>
  </p>

  <p>
    <label>Message:<br />
      <textarea name="message" rows="5" required></textarea>
    </label>
  </p>

  <p>
    <button type="submit">Send Message</button>
  </p>

</form>

---

### Parking Office Information

**Phone:** (555) 123-4567  
**Email:** parking@yourwebsite.com  
**Address:** 123 Main St, Lexington, KY  

</section>

<style>
  .contact-page input, .contact-page textarea {
    width: 100%;
    max-width: 500px;
    padding: 8px;
    margin-top: 4px;
  }
  .contact-page button {
    padding: 10px 18px;
    cursor: pointer;
  }
</style>

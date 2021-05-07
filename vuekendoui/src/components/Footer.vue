<template>
  <div class="footer-container">
    <div class="footer">
      <div class="footer-heading footer-1">
        <h2>About Us</h2>
        <a href="#">Blog</a>
        <a href="#">Demo</a>
        <a href="#">Customers</a>
        <a href="#">Investors</a>
        <a href="#">Terms of Service</a>
      </div>
      <div class="footer-heading footer-2">
        <h2>Contact Us</h2>
        <a href="#">Jobs</a>
        <a href="#">Support</a>
        <a href="#">Contact</a>
        <a href="#">Sponsorships</a>
      </div>
      <div class="footer-heading footer-3">
        <h2>Social Media</h2>
        <a href="#">Instagram</a>
        <a href="#">Facebook</a>
        <a href="#">Youtube</a>
        <a href="#">Twitter</a>
      </div>
      <div class="footer-email-form">
        <h2>Join our newsletter</h2>
        <input
          type="email"
          placeholder="Enter your email address"
          id="footer-email"
        />
        <input type="submit" value="Sign Up" id="footer-email-btn" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  components: {},
};
</script>

<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

.footer-container {
  background-color: #212329;
  padding-bottom: 4rem;
  padding: 6rem 0 2rem 0;
}

.footer {
  width: 80%;
  height: 40vh;
  background-color: #212329;
  color: #fff;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin: 0 auto;
}

.footer-heading {
  display: flex;
  flex-direction: column;
  margin-right: 4rem;
}

.footer-heading h2 {
  margin-bottom: 2rem;
}

.footer-heading a {
  color: #fff;
  text-decoration: none;
  margin-bottom: 0.5rem;
}

.footer-heading a:hover {
  color: red;
  transition: 0.3s ease-out;
}

.footer-email-form h2 {
  margin-bottom: 2rem;
}

#footer-email {
  width: 250px;
  height: 40px;
  border-radius: 4px;
  outline: none;
  border: none;
  padding-left: 0.5rem;
  font-size: 1rem;
  margin-bottom: 1rem;
}

#footer-email::placeholder {
  color: #b1b1b1;
}

#footer-email-btn {
  width: 100px;
  height: 40px;
  border-radius: 4px;
  background-color: #f9423d;
  outline: none;
  border: none;
  color: #fff;
  font-size: 1rem;
}

#footer-email-btn:hover {
  cursor: pointer;
  background-color: #337af1;
  transition: all 0.4s ease-out;
}

@media screen and (max-width: 1150px) {
  .footer {
    height: 50vh;
  }
  .footer-email-form {
    margin-top: 4rem;
  }
}

@media screen and (max-width: 820px) {
  .footer {
    padding-top: 2rem;
  }
}

@media screen and (max-width: 720px) {
  .footer-3 {
    display: none;
  }
  .footer-email-form {
    margin-top: 2rem;
  }
}
</style>

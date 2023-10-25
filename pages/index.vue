<template>
  <section class="box">
    <div class="profile">
      <div class="content">
        <h4 class="heading">
          <span>Want To </span>
          <span style="color: red">Know Me</span>
        </h4>
        <br /><br />
        <p>
          I'm Sudan Sunar, and I'm engaged in the field of software development.
          I have 3 years of experience teaching programming to numerous
          students. If you aspire to grow and become a software engineer, please
          feel free to drop me a message via Email and connect with me on

          <span
            ><a
              href="https://www.facebook.com/sudan.sunar404/"
              style="color: red; text-transform: uppercase; font-weight: bold"
              >Facebook</a
            ></span
          >:<span style="color: red; font-size: 23px"
            >sudansunar078@gmail.com</span
          >. Here are the programming languages that I teach:
        </p>
        <div class="programming-languages">
          <div class="images">
            <img src="~/assets/flutter.jpeg" alt="Flutter" height="60px" />
          </div>

          <div class="images">
            <img src="~/assets/nuxt.jpeg" alt="Nuxt.js" height="60px" />
          </div>
          <div class="images">
            <img src="~/assets/vue.jpeg" alt="Vue.js" height="60px" />
          </div>
          <div class="images">
            <img src="~/assets/css.jpeg" alt="CSS" height="60px" />
          </div>
        </div>

        <div class="programming-languages">
          <div class="images">
            <img src="~/assets/html.jpeg" alt="HTML" height="60px" />
          </div>

          <div class="images">
            <img
              src="~/assets/javascript.jpeg"
              alt="JavaScript"
              height="60px"
            />
          </div>
          <div class="images">
            <img
              src="~/assets/tailwindcss.jpeg"
              alt="Tailwind CSS"
              height="60px"
            />
          </div>
          <div class="images">
            <img src="~/assets/bootstrap.jpeg" alt="Bootstrap" height="60px" />
          </div>
        </div>

        <div class="programming-languages">
          <div class="images">
            <img src="~/assets/mysql.jpeg" alt="MySQL" height="60px" />
          </div>

          <div class="images">
            <img src="~/assets/php.jpeg" alt="PHP" height="60px" />
          </div>
          <div class="images">
            <img src="~/assets/git.jpeg" alt="Git" height="60px" />
          </div>
        </div>
      </div>
    </div>
  </section>

  <div>
    <footer>
      <h3>Learn and grow</h3>
      <p></p>
    </footer>
  </div>
</template>
<style>
body {
  position: relative;
  margin: 0;
  padding: 0;
}

* {
  box-sizing: border-box;
  color: white;
}

.box {
  height: 100vh;
  width: 100%;
}

.profile {
  height: 100vh;
  width: 100vw;
  background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 2)),
    url("assets/coder.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
}

.heading {
  margin-top: 5px;
}

.heading span {
  font-size: 60px;
}

.content {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

p {
  font-size: 18px;
  letter-spacing: 1px;
  line-height: 1.5;
}

p::first-letter {
  font-size: 36px;
  font-weight: bold;
  color: blue;
  text-transform: uppercase;
  text-shadow: 2px 2px #ff6a00;
}

.programming-languages {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: 20px 0;
}

.images {
  margin: 10px;
}

.images img {
  height: auto;
  max-width: 100px;
}

h3 {
  color: green;
  text-align: center;
  font-size: 24px;
  font-weight: bold;
  text-transform: uppercase;
}

/* Media Queries for Responsive Design */
@media screen and (max-width: 768px) {
  .heading span {
    font-size: 40px;
  }
}

@media screen and (max-width: 480px) {
  .heading span {
    font-size: 30px;
  }
  p {
    font-size: 16px;
  }
  p::first-letter {
    font-size: 40px;
  }
  .images img {
    max-width: 80px;
  }
}
</style>

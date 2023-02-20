<script>
export default {
  name: "home",
  data() {
    return {
      show: false,
    };
  },
};
</script>

<template>
  <main>
    <div class="header">
      <h1>FElix <br />gAMMal</h1>
      <div class="navBar">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="portfolio">Portfolio</a></li>
        <li><a href="contact">Contact</a></li>
      </div>
    </div>
    <div class="landingPage">
      <div class="welcome-card">
        <div class="picture">
          <img src="./assets/profilPict.png" alt="" />
        </div>
      </div>
      <div class="social-media">
        <a href="https://instagram.com/gammall" target="_blank"
          ><img src="./assets/instagram.svg" class="instagram"
        /></a>
        <a href="https://soundcloud.com/gammall" target="_blank"
          ><img
            
            src="./assets/soundcloud.svg"
            class="soundcloud"
          />
        </a>
        <a href="https://linkedin.com/in/felix-gammal-02998914a" target="_blank"
          ><img src="./assets/linked-in.svg" class="linked-in" />
          </a
        >
      </div>
    </div>
    <div id="about">
      <div class="me-container">
        <h1>Who am i?</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam iste,
          ex delectus quis consectetur voluptas facere recusandae eos deserunt!
          Quidem modi laudantium ad dignissimos, ducimus ea enim excepturi
          fugiat unde laboriosam architecto nam eligendi incidunt voluptatum
          blanditiis, dolorum odit fuga id doloremque necessitatibus voluptate
          quasi. Est dolore eos numquam, maxime mollitia quidem dolorum culpa,
          soluta rem fugit adipisci at. Asperiores!
        </p>
      </div>
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: rgb(112, 112, 112);
  font-family: "Syncopate", sans-serif;
  overflow-x: hidden !important;
}
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative;
}
.header h1 {
  line-height: 18px;
  color: rgb(0, 0, 0);
  margin-left: 310px;
  margin-top: 40px;
  font-size: 25px;
}
.navBar {
  display: flex;
  justify-content: space-around;
  margin-right: 300px;
  align-items: center;
  height: 100px;
}

li {
  list-style-type: none;
}

li a {
  text-decoration: none;
  color: rgb(0, 0, 0);
  font-size: 14px;
  padding: 40px;
  text-transform: uppercase;
}

a:hover {
  color: rgb(255, 255, 255);
  font-size: 17px;
}

.landingPage {
  display: flex;
  align-items: start;
  justify-content: center;
  gap: 50px;
}
.picture {
  width: 400px;
  height: 400px;
  display: flex;
  background-color: rgb(90, 112, 95);
  margin-top: 200px;
  align-items: center;
  border-radius: 100px;
  overflow: hidden;
}
img {
  width: 100%;
  height: auto;
  margin-top: 100px;
  position: relative;
}

.social-media {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-top: 90px;
  width: 100px;
  align-items: center;
}

.linked-in {
  width: 70px;
  height: auto;
  transition: all 0.5s;
  transform-origin: 50% 50%;
}

.soundcloud {
  width: 70px;
  height: auto;
  transition: all 0.5s;
  transform-origin: 50% 50%;
}

.instagram {
  width: 70px;
  height: auto;
  transition: all 0.5s;
  transform-origin: 50% 50%;
}
.instagram:hover,
.soundcloud:hover,
.linked-in:hover {
  transform: scale(1.2);
  filter: invert();
}
#about {
  height: 100vh;
  width: 100vw;
  background-image: linear-gradient(rgb(112, 112, 112), rgb(45, 54, 45));
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.me-container {
  width: 700px;
  height: 450px;
  background-color: rgb(62, 70, 62);
  margin-left: 50px;
}

.me-container h1,
p {
  color: black;
  font-family: Arial, Helvetica, sans-serif;
  font-weight: bold;
}
</style>

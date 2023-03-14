<template>
  <div class="home">
    <img alt="Solver logo" src="../assets/logo-white.svg" />
    <h1>Solver Media Brand Manual title</h1>
    <p>
      Some text about the point of this manual, what you can find in here, how
      you can use it and what you can do here. Maybe also give some links to the
      most requested things right away (like logo files, etc)
    </p>
    <video id="background-video" autoplay loop muted>
      <source src="../assets/hydrofoorpomp-bg-video.mp4" type="video/mp4" />
    </video>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
  components: {},
};
</script>

<style>
.home {
  width: 100%;
  max-height: 500px;
}

h1 {
  color: white;
}

.home p {
  padding: 30px;
  background: white;
  width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.home img {
  width: 250px;
  height: auto;
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
  padding: 10px;
}

.home:before {
  content: "";
  position: absolute;
  background: rgb(2, 0, 36);
  background: linear-gradient(
    180deg,
    rgba(2, 0, 36, 0.8) 0%,
    rgba(25, 25, 138, 0.1) 35%,
    rgba(0, 212, 255, 0.5) 100%
  );
  border-radius: 5px;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  height: 500px;
  z-index: -1;
}

#background-video {
  width: 100vw;
  height: 500px;
  object-fit: cover;
  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  z-index: -3;
}
</style>

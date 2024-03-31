<template>
  <div style="margin-top: 0" class="row row-cols-1 row-cols-md-3 g-4">
    <div class="col">
      <div class="card h-100">
        <img src="../../src/bubu.png" class="card-img-top" alt="..." />
        <div class="card-body hoverImage">
          <h1 style="cursor: pointer" class="card-title">
            <a
              href="http://facebook.com"
              target="_blank"
              style="text-decoration: none; color: black; font-weight: bold"
              rel="noopener noreferrer"
              >Chart</a
            >
          </h1>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img src="../../src/bubu.png" class="card-img-top" alt="..." />
        <div class="card-body hoverImage">
          <h1 style="cursor: pointer" class="card-title">
            <a
              href="https://x.com/bububibicoinsol?t=Dsw70GKCmqrWzTm8koi2ZQ&s=09"
              target="_blank"
              style="text-decoration: none; color: black; font-weight: bold"
              rel="noopener noreferrer"
              >Twitter</a
            >
          </h1>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img src="../../src/bubu.png" class="card-img-top" alt="..." />
        <div class="card-body hoverImage">
          <h1 style="cursor: pointer" class="card-title">
            <a
              href="https://t.me/bubuCoinBibi"
              target="_blank"
              style="text-decoration: none; color: black; font-weight: bold"
              rel="noopener noreferrer"
              >Telegram</a
            >
          </h1>
        </div>
      </div>
    </div>
    <center><h1 style="font-weight: bold">CA</h1></center>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import "bootstrap/dist/css/bootstrap.min.css";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
<style>
body {
  background-color: beige;
}
.hoverImage {
  transform: scale(1.05);

  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}
.hoverImage:hover {
  background-color: lightblue;
  border-radius: 15px;
}
</style>

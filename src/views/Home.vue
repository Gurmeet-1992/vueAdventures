<template>
  <div class="home">   
    <lund p = "Hiiiiii"/>
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src

import lund from "../components/lund";
import HelloWorld from "../components/HelloWorld";

export default {
  name: "home",
  components: {
    lund,
    HelloWorld
  }
};
</script>

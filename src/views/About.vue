<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h1>from welcomemessage component</h1>
    <WelcomeMessage/>
  </div>
</template>

<script>
import WelcomeMessage from "@/components/WelcomeMessage.vue";

export default {
  name: "about",
  components: {
    WelcomeMessage
  }
};
</script>
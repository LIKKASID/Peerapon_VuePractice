<template>
  <div>
    <h1>Home</h1>
    <card></card>
    <card>2nd Card</card>
    <card
      ><card><card>test</card></card></card
    >
  </div>
</template>

<script>
import card from "./card";
export default {
  components: {
    card,
  },
};
</script>
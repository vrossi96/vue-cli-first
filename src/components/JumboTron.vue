<template>
   <div class="jumbo">
      <Title />
   </div>
</template>

<script>
import Title from "./Title.vue";

export default {
   name: "JumboTron",
   components: {
      Title,
   },
};
</script>

<style>
.jumbo {
   background-image: url(../../public/cool-background.svg);
   background-size: cover;
   background-position: center;
   background-repeat: no-repeat;
   height: 500px;
   display: flex;
   justify-content: center;
   align-items: center;
}
</style>

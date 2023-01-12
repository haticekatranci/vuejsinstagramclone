<template>
  <div class="home">

    <CustomText>Merhaba</CustomText>
    <CustomText tag="p" class="a1">Merhaba</CustomText>
    <CustomText tag="p">Merhaba</CustomText>
    <CustomText tag="p" size="xsmall">Merhaba</CustomText>
    <CustomText tag="p" size="xxsmall">Merhaba</CustomText>


  </div>
</template>

<script>
// @ is an alias to /src
import CustomText from "../components/CustomText.vue"


export default {
  name: "HomeView",
  components: {
    CustomText
  }
};
</script>

<style scoped>
.a1 {
  color: rgb(var(--a72));
}

</style>

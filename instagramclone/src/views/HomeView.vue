<template>
  <div class="home">

    <CustomText>Merhaba</CustomText>
    <CustomText tag="p" class="a1">Merhaba</CustomText>
    <CustomText tag="p">Merhaba</CustomText>
    <CustomText tag="p" size="xsmall">Merhaba</CustomText>
    <CustomText tag="p" size="xxsmall">Merhaba</CustomText>
    <IconHome></IconHome>
    <svg width="100" height="100">
      <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
    </svg>


  </div>
</template>

<script>
// @ is an alias to /src
import CustomText from "../components/CustomText.vue"
import IconHome from '../icons/home.svg'


export default {
  name: "HomeView",
  components: {
    CustomText,
    IconHome
  }
};
</script>

<style scoped>
.a1 {
  color: rgb(var(--a72));
}

</style>

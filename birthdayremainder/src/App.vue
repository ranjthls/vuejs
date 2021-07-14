<template>
<HelloWorld name="testing" phone='23432'/>
</template>

<script>
import HelloWorld from "./components/HelloWorld"
export default {
  name:"App",
  components : {
    HelloWorld
  },
  data() {
    return {
      name: "test",
      phone:"12345"
    }
  }
}
</script>

<style>

</style>
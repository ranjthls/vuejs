<template>
    <div>
        <h1>Hello {{name}}, {{phone}}, {{gender}}, {{value}}</h1>
        <button @click="incrementcount">click</button>
    </div>
</template>

<script>
export default {
    name:"HelloWorld",
    props:{
        name:String,
        phone:String
    },
    data() {
    return {
      gender: "Male",
      value: 0
    }
  },
  methods: {
      incrementcount(){
          this.value = this.value + 1
      }
  }
}
</script>

<style>

</style>
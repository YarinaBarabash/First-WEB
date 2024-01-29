<template>
  <div>
    <input name="myName" v-model="myName" placeholder="Введи имя">
    <button @click="onClick" class="input-botton">
      Нажми меня
    </button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      myName: ""
    };
  },
  methods: {
    onClick() {
      console.log(this.myName);
    }
  }
}
</script>

<style>
.input-botton {
  background-color: aquamarine;
  height: 20px;
  border-radius: 4px;
  border: none;
  transition: all 300ms;
  margin-left: 10px;
}
.input-botton:hover {
 background-color: rgb(107, 227, 227);
}
</style>
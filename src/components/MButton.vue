<script setup>
const props = defineProps({
  text: String
})
</script>

<template>
  <button>{{ props.text }}</button>

</template>

<style scoped>
button{
  background-color: rgb(144, 96, 255);
  color: #fdf5f5;
  border: none;
  border-radius: 5px;
  padding: 10px;
  font-size: 0.9rem;
  cursor: pointer;
  margin: 5px;
}

button:hover{
  background-color: rgb(164, 70, 252);
}
</style>
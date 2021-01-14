<template>
  <div>
    <h1>{{ titulo }}</h1>

    <ul>
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo">
      </li>
    </ul>

  </div>
</template>

<script>
export default {
  data() {

    return {
      titulo: "Alurapic",
      fotos: [
        {
          url: "https://images.unsplash.com/photo-1593874105671-d745ff7ce8ba?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=667&q=80",
          titulo: "cachorro"
        },
        {
          url: "https://images.unsplash.com/photo-1593874105671-d745ff7ce8ba?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=667&q=80",
          titulo: "cachorro"
        }
      ]
    }
  }
}
</script>

<style>

</style>

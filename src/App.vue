<script setup lang="ts">

</script>

<template>
 <main>
  <div>
    <h1>Invited People:</h1>
    <div class="input-container">
      <input type="text" placeholder="Name...">
      <select>
        <option value="">Male</option>
        <option value="">Female</option>
      </select>
    </div>
  </div>
 </main>
</template>

<style scoped>

main{
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(126, 58, 58);
}

input, select {
  width: 100%;
  padding: 5px;
  margin-bottom: 2px;
}

</style>
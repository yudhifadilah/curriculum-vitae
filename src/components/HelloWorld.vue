<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="black">{{ msg }}</h1>
    <h3>
      <a href="https://drive.google.com/file/d/1bOdZH80GYSMeFM9tGSS8ZX4igrs_egAX/view?usp=sharing" target="_blank" rel="noopener">Curiculum Vitae</a> +
      <a href="https://drive.google.com/file/d/199dKqJnl3vJkDhT3klMN0t9bXpgG5C6C/view?usp=sharing" target="_blank" rel="noopener">Portofolio</a>.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>

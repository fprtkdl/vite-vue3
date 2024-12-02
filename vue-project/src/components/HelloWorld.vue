<template>
  <div>
    <h1>{{ title }}</h1>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: import.meta.env.VITE_APP_TITLE,
      message: import.meta.env.VITE_APP_MESSAGE,
    };
  },
};
</script>

<style scoped>
/* 스타일 추가 가능 */
</style>

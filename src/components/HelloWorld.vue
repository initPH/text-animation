<!-- MyBook.vue -->
<template>
  <div>{{ collectionName }}: {{ readersNumber }} {{ book.title }}</div>
  <button @click="readersNumber += 1">1111</button>
</template>

<script>
import { ref, reactive } from 'vue';
import prismjs from 'prismjs';
export default {
  props: {
    collectionName: String,
  },
  setup() {
    const readersNumber = ref(0);
    const book = reactive({ title: 'Vue 3 Guide' });
    let style = document.createElement('style')
    style.innerHTML = `
      html {
        background: red
      }
    `
    document.head.appendChild(style)
    // 暴露给 template
    return {
      readersNumber,
      book,
    };
  },
};
</script>

<!-- MyBook.vue -->
<template>
  <pre id="code"></pre>
</template>

<script lang="ts">
import { ref, reactive } from 'vue';
import prismjs from 'prismjs';
import 'prismjs/themes/prism.css';
export default {
  props: {
    collectionName: String,
  },
  setup() {
    const readersNumber = ref(0);
    const book = reactive({ title: 'Vue 3 Guide' });

    let styleStr = `
    /*
    * 面试官你好，我是Edit，广东惠州人
    * 为您精心准备一份不一样的简历来介绍自己
    * 首先准备一些样式
    */
    *{
        transition: all .8s;
    }
    /* 稍等，在容器上添加点样式 */
    #codeEdit{
        color: #fff;
        background: #1E1E1E;
    }
    #resume{
        box-shadow: -1px 4px 9px 3px rgba(0, 0, 0, .15);
    }
    /* 我需要一点代码高亮 */
    pre#codeEdit{
        color: #CE9e78;
    }
    .token.selector{
        color: rgb(230, 155, 43);
    }
    .token.comment{
        color: #6A9955;
        font-size: 14px;
    }
    .token.property{
        color: #60C8FE;
    }
    .token.function {
        color: #DD4A68;
    }
    /* 接下来请欣赏我的个人简历吧 */
`;
    let num = 0;
    let styleTag = document.createElement('style');
    document.head.appendChild(styleTag);
    let interval = setInterval(() => {
      if (num < styleStr.length) {
        document.querySelector('#code').innerHTML = prismjs.highlight(
          styleStr.slice(0, num),
          prismjs.languages.css,
        ) as string;
        num++;

        styleTag.innerHTML = styleStr.slice(0, num);
      } else {
        clearInterval(interval);
      }
    }, 50);

    let style = document.createElement('style');
    // document.head.appendChild(style)

    // 暴露给 template
    return {
      readersNumber,
      book,
    };
  },
};
</script>

import vueCounter from "./vueCounter";
import { createApp } from "vue/dist/vue.esm-bundler";
createApp({
  setup() {
    // カウンターを更新する
    const { counter } = vueCounter();
    return {
      counter,
    };
  },
}).mount("#counter");
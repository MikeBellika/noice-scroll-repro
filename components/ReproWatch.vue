<script setup lang="ts">
const { hello } = defineProps<{
  hello: {
    user: string;
    password: string;
    a: string;
    b: string;
    c: string;
    d: string;
    e: string;
    f: string;
    a1: string;
    b1: string;
    c1: string;
    d1: string;
    e1: string;
    f1: string;
  };
}>();

watch(hello, (newHello) => {
  console.log(newHello);
});
</script>
<template>Hello world</template>

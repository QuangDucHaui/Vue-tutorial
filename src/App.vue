<template>
<div>
<about_page></about_page>
<Homeview></Homeview>
<h1>{{ message }}</h1>
</div>
</template>

<script setup>
import about_page from './components/About.vue';
import Homeview from './components/Homeview.vue';
import { ref } from 'vue';
const checked = ref(true)
const message = ref('hello')
const check = ref(false)
</script>
<style scoped >

</style>


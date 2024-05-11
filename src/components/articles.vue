<script setup>
   import { onMounted } from 'vue';

const url = 'http://localhost:8888/wordpress/wp-json/wp/v2/posts';

    onMounted(() => {
        console.log('mounted');
        fetch(url)
        .then(response => response.json())
        .then(data => console.log(data)); 

    });
    
</script>

<template>
    ciao!
</template>


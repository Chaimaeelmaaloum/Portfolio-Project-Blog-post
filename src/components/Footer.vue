<template lang="">

    <footer class="py-3 my-4">
        <ul class="nav justify-content-center border-bottom pb-3 mb-3">
        <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Home</a></li>
        <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Blog</a></li>
        <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Contact</a></li>
        </ul>
        <p class="text-center text-muted">{{ title }}</p>
  </footer>
</template>


<script>
    export default {
        props:["title"]
    };
</script>


<style lang="">
</style>

<script setup lang="ts">
    // import Header from '@/components/App/Header.vue'
</script>

<template>
    <div>
        <!-- <Header /> -->
        <AppHeader />

        <div class="container px-4 py-4 mx-auto max-w-7xl lg:px-8 sm:px-0">
          <slot />
        </div>
        
        <AppFooter />
    </div>
</template>

<style scoped>

</style>
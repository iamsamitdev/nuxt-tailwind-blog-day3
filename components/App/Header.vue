<script setup lang="ts">

</script>

<template>
    <header class="bg-white">
        <nav class="flex items-center justify-between p-6 mx-auto max-w-7xl lg:px-8">
            <div class="flex lg:flex-1">
                <NuxtLink to="/" class="-m-1.5 p-1.5">
                    <span class="font-bold">NUXT3 BLOG</span>
                </NuxtLink>
            </div>
            <div class="flex lg:hidden">
                <button type="button" class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-gray-700">
                    <span class="sr-only">Open main menu</span>
                    <svg class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                    </svg>
                </button>
            </div>
            <div class="hidden lg:flex lg:gap-x-12">
                
                <NuxtLink to="/" 
                class="text-sm font-semibold leading-6 text-gray-900">
                Home
                </NuxtLink>
                <NuxtLink to="/categories" 
                class="text-sm font-semibold leading-6 text-gray-900">
                Categories
                </NuxtLink>
                <NuxtLink to="/contact" 
                class="text-sm font-semibold leading-6 text-gray-900">
                Contact
                </NuxtLink>

            </div>
            <div class="hidden lg:flex lg:flex-1 lg:justify-end">
                <a href="#" class="text-sm font-semibold leading-6 text-gray-900">Log in</a>
            </div>
        </nav>
    </header>
</template>


<style scoped>

</style>
<script setup lang="ts">

</script>

<template>
    <section>
        <div class="container mx-auto">
            <div class="flex flex-wrap gap-5">
                <NuxtLink 
                    to="/categories/category1"
                    class="flex items-center justify-center px-4 py-2 text-2xl text-white uppercase duration-200 rounded shadow-md hover:shadow-lg"
                    :style="{ backgroundColor: colorGenerator() }"
                    >
                    <span class="font-semibold">#Category 1</span>
                </NuxtLink>

                <NuxtLink 
                    to="/categories/category2"
                    class="flex items-center justify-center px-4 py-2 text-2xl text-white uppercase duration-200 rounded shadow-md hover:shadow-lg"
                    :style="{ backgroundColor: colorGenerator() }"
                    >
                    <span class="font-semibold">#Category 2</span>
                </NuxtLink>

            </div>
        </div>
    </section>
</template>

<style scoped>

</style>
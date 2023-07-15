<template>
<footer class="p-4 text-gray-200 rounded-lg shadow font-poppin md:px-6 md:py-8 bg-neutral-800 bg-grad">
    <div class="container w-11/12 pb-8 mx-auto sm:pb-10 sm:w-9/12 md:w-7/12">
    <div class="mb-10 sm:flex sm:items-center sm:justify-between">
        <RouterLink to="/" class="flex items-center mb-4 sm:mb-0">
            <img src="../assets/cd/wollogovec.png" loading="lazy" class="h-8 mr-3 animate-spin-slow" alt="Flowbite Logo" />
            <span class="self-center text-2xl font-semibold text-white  whitespace-nowrap">WOLMER</span>
        </RouterLink>
    </div>
    <hr class="my-6 border-gray-700 sm:mx-auto lg:my-8" />
    <span class="block text-sm text-gray-400 sm:text-center">This Website is Open Source <a href="https://github.com/thewolmer/WolPortal" class=" linked-white">on Github</a>. 
    </span>
    
</div>
</footer>


    
</template>

<script>
export default {
    name: 'Footer'
}
</script>

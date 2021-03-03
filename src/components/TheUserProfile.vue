<template>
    <figure class="bg-gray-100 rounded-xl p-8">
    <img class="w-32 h-32 rounded-full mx-auto" :src="photo" alt="" width="384" height="512">
    <div class="pt-6 text-center space-y-4">
        <blockquote>
        <p class="text-lg font-semibold">
            “Tailwind CSS is the only framework that I've seen scale
            on large teams. It’s easy to customize, adapts to any design,
            and the build size is tiny.”
        </p>
        </blockquote>
        <figcaption class="font-medium">
        <div class="text-cyan-600">
            Chanty SOK
        </div>
        <div class="text-gray-500">
            Software Engineer, Cambodia
        </div>
        </figcaption>
    </div>
    </figure>    
</template>

<script>
    export default {
        name: "user-profile",
        data()  {
            return {
                photo: './assets/my-photo.jpg'
            }
        }
    }
</script>
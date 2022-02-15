<template>
    <div class="bg-yellow-500 text-green-700">
    <div class="container mx-auto flex items-center justify-between">
        <h1 class="tracking-tighter text-3xl font-thin">Basic<span class="font-normal">Router</span></h1>
        <nav>
            <ul class="flex space-x-4">
                <router-link to="/"><li class="py-8 px-4 hover:cursor-pointer hover:bg-gray-400 hover:text-red-700">Home</li> </router-link>
                <router-link to="/about"><li class="py-8 px-4 hover:cursor-pointer hover:bg-gray-400 hover:text-red-700">About</li></router-link>
                <router-link to="/hello"><li class="py-8 px-4 hover:cursor-pointer hover:bg-gray-400 hover:text-red-700">Hello</li> </router-link>
            </ul>
        </nav>
    </div>
    </div>
</template>
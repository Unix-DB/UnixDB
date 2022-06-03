<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import GuestNavigation from "./GuestNavigation";
</script>

<template>
    <GuestNavigation></GuestNavigation>
    <div class="relative bg-white overflow-hidden">
        <div class="pt-16 pb-80 sm:pt-24 sm:pb-40 lg:pt-40 lg:pb-48">
            <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 sm:static">
                <div class="sm:max-w-lg">
                    <h1 class="text-4xl font font-extrabold tracking-tight text-gray-900 sm:text-6xl">Unix DB</h1>
                    <p class="mt-4 text-xl text-gray-500">Place where you can share your riced setups for free all in one platform.</p>
                </div>
                <div>
                    <div class="mt-10">
                        <!-- Decorative image grid -->
                        <div aria-hidden="true" class="pointer-events-none lg:absolute lg:inset-y-0 lg:max-w-7xl lg:mx-auto lg:w-full">
                            <div class="absolute transform sm:left-1/2 sm:top-0 sm:translate-x-8 lg:left-1/2 lg:top-1/2 lg:-translate-y-1/2 lg:translate-x-8">
                                <div class="flex items-center space-x-6 lg:space-x-8">
                                    <div class="flex-shrink-0 grid grid-cols-1 gap-y-6 lg:gap-y-8">
                                        <div class="w-44 h-64 rounded-lg overflow-hidden sm:opacity-0 lg:opacity-100">
                                            <img src="https://preview.redd.it/va4rqvfnk6391.png?width=640&crop=smart&auto=webp&s=8986e1a4e71e675303237de048c21135d2c6d09a" alt="" class="w-full h-full object-center object-cover" />
                                        </div>
                                        <div class="w-44 h-64 rounded-lg overflow-hidden">
                                            <img src="https://preview.redd.it/1898qkqgo2391.png?width=640&crop=smart&auto=webp&s=8a040c742676631f73cf870af8f7a06fbba698fb" alt="" class="w-full h-full object-center object-cover" />
                                        </div>
                                    </div>
                                    <div class="flex-shrink-0 grid grid-cols-1 gap-y-6 lg:gap-y-8">
                                        <div class="w-44 h-64 rounded-lg overflow-hidden">
                                            <img src="https://preview.redd.it/hsob84nrn4391.png?width=640&crop=smart&auto=webp&s=d46c8005a9796d64ec52d9ce713c7653cf73e9e4" alt="" class="w-full h-full object-center object-cover" />
                                        </div>
                                        <div class="w-44 h-64 rounded-lg overflow-hidden">
                                            <img src="https://preview.redd.it/80scsq5k06391.png?width=640&crop=smart&auto=webp&s=0fecc2914b371305c25b4368520a9a1ca95b8036" alt="" class="w-full h-full object-center object-cover" />
                                        </div>
                                        <div class="w-44 h-64 rounded-lg overflow-hidden">
                                            <img src="https://preview.redd.it/8helhmt545391.jpg?width=640&crop=smart&auto=webp&s=3cd2600bf4ecd6cdc77a49b98bb3ba97dd123bab" alt="" class="w-full h-full object-center object-cover" />
                                        </div>
                                    </div>
                                    <div class="flex-shrink-0 grid grid-cols-1 gap-y-6 lg:gap-y-8">
                                        <div class="w-44 h-64 rounded-lg overflow-hidden">
                                            <img src="https://preview.redd.it/vulf2liqy0391.png?width=640&crop=smart&auto=webp&s=ef02e35e0cc52a2d9f11e2f0a1367861f4f9ce94" alt="" class="w-full h-full object-center object-cover" />
                                        </div>
                                        <div class="w-44 h-64 rounded-lg overflow-hidden">
                                            <img src="https://i.imgur.com/44Yvs0Vl.png" alt="" class="w-full h-full object-center object-cover" />
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <a href="/register" class="inline-block text-center bg-indigo-600 border border-transparent rounded-md py-3 px-8 font-medium text-white hover:bg-indigo-700">Get Started</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

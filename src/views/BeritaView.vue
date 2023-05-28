<template>
    <!-- Carousel -->
    <div class="flex gap-4 mx-auto bg-slate-200 mt-10">
        <div id="controls-carousel" class="relative w-full" data-carousel="static">
            <!-- Carousel wrapper -->
            <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
                <!-- Item 1 -->
                <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img src="../assets/Card1.png"
                        class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
                </div>
                <!-- Item 2 -->
                <div class="hidden duration-700 ease-in-out" data-carousel-item="active">
                    <img src="../assets/Card1.png"
                        class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
                </div>
                <!-- Item 3 -->
                <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img src="../assets/Card1.png"
                        class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
                </div>
                <!-- Item 4 -->
                <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img src="../assets/Card1.png"
                        class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
                </div>
                <!-- Item 5 -->
                <div class="hidden duration-700 ease-in-out" data-carousel-item>
                    <img src="../assets/Card1.png"
                        class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
                </div>
            </div>
            <!-- Slider controls -->
            <button type="button"
                class="absolute top-0 left-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none"
                data-carousel-prev>
                <span
                    class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
                    <svg aria-hidden="true" class="w-6 h-6 text-white dark:text-gray-800" fill="none" stroke="currentColor"
                        viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"></path>
                    </svg>
                    <span class="sr-only">Previous</span>
                </span>
            </button>
            <button type="button"
                class="absolute top-0 right-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none"
                data-carousel-next>
                <span
                    class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
                    <svg aria-hidden="true" class="w-6 h-6 text-white dark:text-gray-800" fill="none" stroke="currentColor"
                        viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
                    </svg>
                    <span class="sr-only">Next</span>
                </span>
            </button>
        </div>
    </div>
    <!-- End of Carousel -->
    <!-- Card Berita -->
    <section class="container mx-auto mt-10 mb-8">
        <div class="text-start flex flex-col">
            <h1 class="font-bold md:text-3xl text-2xl text-[#3f3f3f] ml-8">Berita Olahraga</h1>
        </div>
        <div class="grid grid-cols-1 gap-2 justify-center pb-[10%] pt-0 md:grid-cols-3 md:gap-10 mr-10 ml-10">
            <div
                class="max-w-full rounded overflow-hidden shadow-lg bg-white mt-4 justify-end hover:scale-105 transition-all duration-300">
                <img class="w-full" src="https://www.rmoljatim.id/uploads/images/2022/08/image_750x_630aeff087039.jpg"
                    alt="Sunset in the mountains">
                <div class="px-6 py-4">
                    <h2 class="font-bold text-xl mb-2 text-gray-600 text-start">Kejuaraaan Nasional</h2>
                    <p class="text-gray-700 font-medium mb-2 text-start">Yogyakarta, 3 Mei 2022</p>
                    <button type="button"
                        class="text-white bg-red-600 hover:bg-red-700 focus:ring-4 focus:outline-none focus:ring-blue-200 dark:focus:ring-blue-900 font-medium rounded-lg text-sm px-5 py-2.5 inline-flex justify-center w-full text-center">Lihat
                        Selengkapnya</button>
                </div>
            </div>
            <div
                class="max-w-full rounded overflow-hidden shadow-lg bg-white mt-4 justify-end hover:scale-105 transition-all duration-300">
                <img class="w-full"
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEMgxa_3L6YVCO8dqBSEdWeTX1_4UYcLtUoG5MU7AglAQL8dww8CAsXOVawjeCc7gUYsU&usqp=CAU"
                    alt="Sunset in the mountains">
                <div class="px-6 py-4">
                    <h2 class="font-bold text-xl mb-2 text-gray-600 text-start">Kejuaraaan Nasional</h2>
                    <p class="text-gray-700 font-medium mb-2 text-start">Yogyakarta, 3 Mei 2022</p>
                    <button type="button"
                        class="text-white bg-red-600 hover:bg-red-700 focus:ring-4 focus:outline-none focus:ring-blue-200 dark:focus:ring-blue-900 font-medium rounded-lg text-sm px-5 py-2.5 inline-flex justify-center w-full text-center">Lihat
                        Selengkapnya</button>
                </div>
            </div>
            <div
                class="max-w-full rounded overflow-hidden shadow-lg bg-white mt-4 justify-end hover:scale-105 transition-all duration-300">
                <img class="w-full" src="https://www.rmoljatim.id/uploads/images/2022/08/image_750x_630aeff087039.jpg"
                    alt="Sunset in the mountains">
                <div class="px-6 py-4">
                    <h2 class="font-bold text-xl mb-2 text-gray-600 text-start">Kejuaraaan Nasional</h2>
                    <p class="text-gray-700 font-medium mb-2 text-start">Yogyakarta, 3 Mei 2022</p>
                    <button type="button"
                        class="text-white bg-red-600 hover:bg-red-700 focus:ring-4 focus:outline-none focus:ring-blue-200 dark:focus:ring-blue-900 font-medium rounded-lg text-sm px-5 py-2.5 inline-flex justify-center w-full text-center">Lihat
                        Selengkapnya</button>
                </div>
            </div>
            <div
                class="max-w-full rounded overflow-hidden shadow-lg bg-white mt-4 justify-end hover:scale-105 transition-all duration-300">
                <img class="w-full" src="https://www.rmoljatim.id/uploads/images/2022/08/image_750x_630aeff087039.jpg"
                    alt="Sunset in the mountains">
                <div class="px-6 py-4">
                    <h2 class="font-bold text-xl mb-2 text-gray-600 text-start">Kejuaraaan Nasional</h2>
                    <p class="text-gray-700 font-medium mb-2 text-start">Yogyakarta, 3 Mei 2022</p>
                    <button type="button"
                        class="text-white bg-red-600 hover:bg-red-700 focus:ring-4 focus:outline-none focus:ring-blue-200 dark:focus:ring-blue-900 font-medium rounded-lg text-sm px-5 py-2.5 inline-flex justify-center w-full text-center">Lihat
                        Selengkapnya</button>
                </div>
            </div>
            <div
                class="max-w-full rounded overflow-hidden shadow-lg bg-white mt-4 justify-end hover:scale-105 transition-all duration-300">
                <img class="w-full"
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEMgxa_3L6YVCO8dqBSEdWeTX1_4UYcLtUoG5MU7AglAQL8dww8CAsXOVawjeCc7gUYsU&usqp=CAU"
                    alt="Sunset in the mountains">
                <div class="px-6 py-4">
                    <h2 class="font-bold text-xl mb-2 text-gray-600 text-start">Kejuaraaan Nasional</h2>
                    <p class="text-gray-700 font-medium mb-2 text-start">Yogyakarta, 3 Mei 2022</p>
                    <button type="button"
                        class="text-white bg-red-600 hover:bg-red-700 focus:ring-4 focus:outline-none focus:ring-blue-200 dark:focus:ring-blue-900 font-medium rounded-lg text-sm px-5 py-2.5 inline-flex justify-center w-full text-center">Lihat
                        Selengkapnya</button>
                </div>
            </div>
            <div
                class="max-w-full rounded overflow-hidden shadow-lg bg-white mt-4 justify-end hover:scale-105 transition-all duration-300">
                <img class="w-full" src="https://www.rmoljatim.id/uploads/images/2022/08/image_750x_630aeff087039.jpg"
                    alt="Sunset in the mountains">
                <div class="px-6 py-4">
                    <h2 class="font-bold text-xl mb-2 text-gray-600 text-start">Kejuaraaan Nasional</h2>
                    <p class="text-gray-700 font-medium mb-2 text-start">Yogyakarta, 3 Mei 2022</p>
                    <button type="button"
                        class="text-white bg-red-600 hover:bg-red-700 focus:ring-4 focus:outline-none focus:ring-blue-200 dark:focus:ring-blue-900 font-medium rounded-lg text-sm px-5 py-2.5 inline-flex justify-center w-full text-center">Lihat
                        Selengkapnya</button>
                </div>
            </div>
        </div>
    </section>
    <!-- End of Card Berita -->
</template>

<script setup>

</script>
<template>
    <nav class="bg-white px-2 sm:px-4 py-2.5 dark:bg-gray-500 fixed w-full z-20 top-0 left-0 border-b border-gray-200 dark:border-gray-500">
      <div class="container flex flex-wrap items-center justify-between mx-auto">
        <!-- logo -->
        <div class="flex items-center">
          <img src="~/assets/logo.png" class="mr-4 sm:h-11" alt="Translateasy logo" />
          <span class="self-center text-xl font-semibold whitespace-nowrap dark:text-white">Translateasyy</span>
        </div>
        <!-- language -->
        <div class="flex md:order-2">
          <select
            id="countries"
            class="bg-gray-50 border border-gray-300  text-gray-900 text-sm rounded-lg focus:ring-gray-500 focus:border-gray-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-gray-500 dark:focus:border-gray-500 focus:ring-2"
          >
            <option selected>Indonesia</option>
            <option value="US">English</option>
          </select>
        </div>
      <div class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1" id="navbar-sticky">
        <ul class="flex flex-col p-4 mt-4  md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
          <li>
            <NuxtLink to="/" class="block py-2 pl-3 pr-4 text-gray-400 md:p-0 md:dark:hover:text-white 
            ">Translator</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about" class="block py-2 pl-3 pr-4 text-white md:p-0">About</NuxtLink>
          </li>
        </ul>
      </div>
      </div>
    </nav>

    <div class="min-h-screen bg-slate-50 dark:bg-white dark:text-white">
    <div class="max-w-4xl mx-auto">
      <section id="hero"
            class="flex flex-col-reverse justify-center sm:flex-row p-6 items-center gap-8 mb-12 scroll-mt-40 widescreen:section-min-height tallscreen:section-min-height">
            <article class="sm:w-1/2">
                <h2
                    class="max-w-md text-4xl font-bold text-center sm:text-5xl sm:text-left text-slate-900 dark:text-white">
                    We Boldy Go <span class="text-indigo-700 dark:text-indigo-300">Where No Rocket</span> Has Gone
                    Before...
                </h2>
                <p class="max-w-md text-2xl mt-4 text-center sm:text-left text-slate-700 dark:text-slate-400">
                    We're building rockets for the next century today. From the moon to Mars, Jupiter and beyond...
                </p>
                <p class="max-w-md text-2xl mt-4 text-center sm:text-left text-slate-700 dark:text-slate-400">
                    Think Acme Rockets.
                </p>
            </article>
            <img class="w-1/2" src="~/assets/book.jpg" alt="Book">
        </section>
        <hr class="mx-auto bg-black dark:bg-white w-1/2">

<section id="rockets"
    class="p-6 my-12 scroll-mt-20 widescreen:section-min-height tallscreen:section-min-height">
    <h2 class="text-4xl font-bold text-center sm:text-5xl mb-6 text-slate-900 dark:text-white">
        Our Rockets
    </h2>
    <ul class="list-none mx-auto my-12 flex flex-col sm:flex-row items-center gap-8">
        <li
            class="w-2/3 sm:w-5/6 flex flex-col items-center border border-solid border-slate-900 dark:border-gray-100 bg-white dark:bg-black py-6 px-2 rounded-3xl shadow-xl">
            <img src="./img/rocketman.png" alt="Explorer" class="w-1/2 mb-6">
            <h3 class="text-3xl text-center text-slate-900 dark:text-white">Explorer</h3>
            <p class="hidden sm:block text-3xl text-center mt-2 text-slate-500 dark:text-slate-400">$</p>
            <p class="sm:hidden text-2xl text-center mt-2 text-slate-500 dark:text-slate-400">Affordable
                Exploration</p>
        </li>
        <li
            class="w-2/3 sm:w-5/6 flex flex-col items-center border border-solid border-slate-900 dark:border-gray-100 bg-white dark:bg-black py-6 px-2 rounded-3xl shadow-xl">
            <img src="./img/rocketride.png" alt="Adventurer" class="w-1/2 mb-6">
            <h3 class="text-3xl text-center text-slate-900 dark:text-white">Adventurer</h3>
            <p class="hidden sm:block text-3xl text-center mt-2 text-slate-500 dark:text-slate-400">$$</p>
            <p class="sm:hidden text-2xl text-center mt-2 text-slate-500 dark:text-slate-400">Best Selling
                Rocket!</p>
        </li>
        <li
            class="w-2/3 sm:w-5/6 flex flex-col items-center border border-solid border-slate-900 dark:border-gray-100 bg-white dark:bg-black py-6 px-2 rounded-3xl shadow-xl">
            <img src="./img/rocketlaunch.png" alt="Infinity" class="w-1/2 mb-6">
            <h3 class="text-3xl text-center text-slate-900 dark:text-white">Infinity</h3>
            <p class="hidden sm:block text-3xl text-center mt-2 text-slate-500 dark:text-slate-400">$$$</p>
            <p class="sm:hidden text-2xl text-center mt-2 text-slate-500 dark:text-slate-400">Luxury Starship
            </p>
        </li>
    </ul>
</section>
    </div>
  </div>
    </template>
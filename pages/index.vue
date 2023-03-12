<template>
  <div class="h-screen bg-gray-200">
    <nav
      class="bg-white px-2 sm:px-4 py-2.5 dark:bg-gray-500 fixed w-full z-20 top-0 left-0 border-b border-gray-200 dark:border-gray-500"
    >
      <div
        class="container flex flex-wrap items-center justify-between mx-auto"
      >
        <!-- logo -->
        <div class="flex items-center">
          <img
            src="~/assets/logo.png"
            class="mr-4 sm:h-11"
            alt="Translateasy logo"
          />
          <span
            class="self-center text-xl font-semibold whitespace-nowrap dark:text-white"
            >Translateasyy</span
          >
        </div>
        <!-- profile -->
        <div class="flex md:order-2">
          <button>
            <img
              src="~/assets/profile.png"
              class="sm:h-18"
              alt="Profile logo"
            />
          </button>
        </div>
        <div
          class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1"
          id="navbar-sticky"
        >
          <ul
            class="flex flex-col p-4 mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium"
          >
            <li>
              <NuxtLink to="/" class="block py-2 pl-3 pr-4 text-white md:p-0"
                >Translator</NuxtLink
              >
            </li>
            <li>
              <NuxtLink
                to="/about"
                class="block py-2 pl-3 pr-4 text-gray-400 md:p-0 md:dark:hover:text-white"
                >About</NuxtLink
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- isi -->
    <form class="bg-white rounded-2xl container mx-auto translate-y-[14vh]"> 
    <div>
      <select
        name="bhs"
        id="bhs"
        class="px-5 mt-10 mx-10 rounded-2xl bg-pink-500 rounded-2xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 text-black"
      >
        <option value="en">ENGLISH</option>
        <option value="id">INDO</option>
      </select>
    </div>
    <div class="py-5 px-10">
      <input
        id="text"
        class="p-5 min-w-full text-center rounded-xl bg-gray-100 rounded-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 focus:outline-none text-white placeholder:text-gray-100"
        type="text"
        placeholder="type here"
      /><br />

      <div>
        <select
          name="trans"
          id="trans"
          class="px-5 mt-10 mx-auto rounded-3xl bg-gray-100 rounded-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 text-white"
        >
          <option value="en">ENGLISH</option>
          <option value="id">INDO</option>
        </select>
        <div class="py-5 px-10">
          <input
            id="text"
            class="p-5 min-w-full text-center rounded-xl bg-gray-100 rounded-3xl bg-clip-padding backdrop-filter backdrop-blur-sm bg-opacity-10 focus:outline-none text-white placeholder:text-gray-100"
            type="text"
            placeholder="type here"
          /><br />
        </div>
      </div>
      <br />
      <div class="flex justify-evenly">
        <button type="submit" class="text-white font-semibold">Speak</button>
        <button type="submit" class="text-white font-semibold">
          Translate
        </button>
        <button type="submit" class="text-white font-semibold">Fusion</button>
      </div>
      <section id="translate" class="text-center pt-6 pb-2"></section>
    </div>
  </form>
    <!-- </div> -->
  </div>
</template>

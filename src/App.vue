<template>
  <div class="min-h-screen bg-sky-400">

    <!-- NAVBAR -->
    <nav
      class="flex items-center justify-between
             px-10 py-5
             bg-sky-500 shadow-xl"
    >

      <!-- LEFT SIDE -->
      <div class="flex items-center gap-5">

        <!-- LOGO -->
        <div
          class="bg-white p-2 rounded-2xl shadow-lg"
        >
          <img
            src="./assets/SOS.png"
            alt="SOS Logo"
            class="w-24 h-24 object-contain"
          />
        </div>

        <!-- TITLE -->
        <div class="leading-tight">

          <h1
            class="text-white text-4xl font-extrabold tracking-wide"
          >
            SOS CHILDREN'S
          </h1>

          <h2
            class="text-white text-4xl font-extrabold tracking-wide"
          >
            VILLAGES
          </h2>

        </div>

      </div>

      <!-- NAVIGATION -->
      <div
        class="flex items-center gap-8
               text-white text-xl font-bold"
      >

        <router-link
          to="/"
          class="hover:text-yellow-300 transition duration-300"
        >
          Home
        </router-link>

        <span class="text-white/60">|</span>

        <router-link
          to="/about"
          class="hover:text-yellow-300 transition duration-300"
        >
          About
        </router-link>

      </div>

    </nav>

    <!-- PAGE CONTENT -->
    <main class="p-10">
      <router-view />
    </main>

  </div>
</template>
<script setup>
</script>
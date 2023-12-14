<template>
  <link rel="stylesheet" href="https://rsms.me/inter/inter.css">
  <div class="h-screen bg-zinc-900">
    <NuxtLayout>
      <div class="h-full">
        <div class="bg-zinc-900">
          <Header/>
          <div class="relative isolate pt-14">
            <div class="absolute inset-x-0 -top-40 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80"
                 aria-hidden="true">
              <div
                  class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-20 sm:left-[calc(50%-30rem)] sm:w-[72.1875rem]"
                  style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"/>
            </div>
            <div class="pt-24 sm:py-32 lg:pb-10">
              <div class="mx-auto max-w-7xl px-6 lg:px-8">
                <NuxtPage/>
              </div>
            </div>
            <div
                class="absolute inset-x-0 top-[calc(100%-13rem)] -z-10 transform-gpu overflow-hidden blur-3xl sm:top-[calc(100%-30rem)]"
                aria-hidden="true">
              <div
                  class="relative left-[calc(50%+3rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-20 sm:left-[calc(50%+36rem)] sm:w-[72.1875rem]"
                  style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"/>
            </div>
          </div>
        </div>
        <Footer/>
      </div>

    </NuxtLayout>
  </div>
</template>
<script setup lang="ts">

</script>

<style>
.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}

.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}

.router-link-active{
  @apply text-white !important;
}

body::-webkit-scrollbar-track
{
  //-webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.6);
  background-color: rgba(24, 24, 27);
}

body::-webkit-scrollbar
{
  width: 10px;
  background-color: rgba(245, 245, 245, 0.99);
}

body::-webkit-scrollbar-thumb
{
  background-color: rgba(24, 24, 27, 0.84);
  background-image: -webkit-linear-gradient(90deg,
  rgba(0, 0, 0, 1) 0%,
  rgba(0, 0, 0, 1) 25%,
  transparent 100%,
  rgba(0, 0, 0, 1) 75%,
  transparent)
}
</style>
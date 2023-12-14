<template>
  <div>
    <ul aria-label="Changelog feed" role="feed"
        class="relative flex flex-col gap-12 py-12 pl-6 before:absolute before:top-0 before:left-6 before:h-full before:border before:-translate-x-1/2 before:border-slate-200 before:border-dashed after:absolute after:top-6 after:left-6 after:bottom-6 after:border after:-translate-x-1/2 after:border-slate-200 ">
      <li role="article"
          class="relative pl-6 before:absolute before:z-10 before:left-0 before:top-2 before:h-2 before:w-2 before:-translate-x-1/2 before:rounded-full before:bg-red-500 before:ring-2 before:ring-white">
        <div class="flex flex-col flex-1 gap-4">
          <h4 class="text-lg font-medium text-red-500">v1.0.0 <span class="text-lg font-normal text-white"> - 2023-02-08</span>
          </h4>
          <p class=" text-slate-300">This provides a very significant performance boost on pages with a huge number of
            DOM nodes, but there's a chance it could be a breaking change in very rare edge cases we haven't thought of.
            Update several dependencies, including postcss-js.</p>
        </div>
      </li>
      <li role="article"
          class="relative pl-6 before:absolute before:z-10 before:left-0 before:top-2 before:h-2 before:w-2 before:-translate-x-1/2 before:rounded-full before:bg-red-500 before:ring-2 before:ring-white">
        <div class="flex flex-col flex-1 gap-4">
          <h4 class="text-lg font-medium text-red-500">Started <span class="text-lg font-normal text-white"> - 2023-01-08</span>
          </h4>
        </div>
      </li>
<!--      <li role="article"-->
<!--          class="relative pl-6 before:absolute before:z-10 before:left-0 before:top-2 before:h-2 before:w-2 before:-translate-x-1/2 before:rounded-full before:bg-red-500 before:ring-2 before:ring-white">-->
<!--        <div class="flex flex-col flex-1 gap-4">-->
<!--          <h4 class="text-lg font-medium text-red-500">v1.2.5 <span class="text-lg font-normal text-white"> - 2023-01-21</span>-->
<!--          </h4>-->
<!--          <p class="text-slate-300">Pass extended color palette to theme closures so it can be used without installing-->
<!--            Tailwind when using npx tailwindcss.</p>-->
<!--          <ul class="pl-5 list-disc text-slate-300 marker:text-red-500">-->
<!--            <li>Remove outdated focus style fix in Preflight</li>-->
<!--            <li>Fix error when not using a config file with postcss</li>-->
<!--            <li>Fix issue with resolveConfig not being importable in Next.js</li>-->
<!--          </ul>-->
<!--        </div>-->
<!--      </li>-->
    </ul>
  </div>
</template>

<style scoped>

</style>
<script setup lang="ts">
</script>
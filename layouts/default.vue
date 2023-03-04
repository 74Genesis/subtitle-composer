<script lang="ts" setup>
</script>

<template>
  <div
    class="relative mx-auto flex min-h-screen w-full grow flex-col bg-white shadow"
  >
    <header
      id="header"
      class="mx-auto flex w-full max-w-7xl flex-col justify-center"
    >
      test footer
    </header>
    <main
      id="main"
      class="flex h-full grow flex-col items-center overflow-y-auto bg-white"
    >
      <div class="w-full bg-white md:mb-6 md:p-10">
        <slot />
      </div>
    </main>
    <footer id="footer" class="bg-red-800">footer</footer>
  </div>
</template>

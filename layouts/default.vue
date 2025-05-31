<script setup lang="ts"></script>

<template>
  <!-- Main class wraps everything -->
  <main class="flex flex-col gap-y-3 relative m-auto w-7xl h-full">
    <HeaderNavBar />
    <!-- Page content -->
    <slot />
  </main>
</template>

<!-- NOTE: The style here is intentionally global to modify `#__nuxt` -->
<style>
div#__nuxt {
  @apply relative flex w-screen h-full;
}
</style>

<script setup lang="ts"></script>

<template>
  <!-- Wrapper -->
  <div
    class="relative flex flex-col gap-y-4 pt-4 bg-surface-0 hover:shadow-xs rounded-md overflow-hidden duration-300 border border-surface-200 transition-all"
  >
    <!-- Header -->
    <div class="relative flex flex-col gap-y-2 px-4">
      <!-- Job Title -->
      <h1
        class="tracking-normal leading-7 font-bold text-surface-800 text-xl text-left"
      >
        Looking for Frontend Developers
      </h1>

      <div class="relative flex flex-row items-center justify-between">
        <!-- Share box -->
        <div
          class="relative flex flex-row items-center justify-start gap-x-1.5"
        >
          <!-- avatar -->
          <PrimeAvatar
            class="avatar"
            image="https://lh3.googleusercontent.com/a/ACg8ocKRV5wc4BFUYdu0gprJebAVQVi81hV1a1pc2s3dUzMU9vJKsVXR=s288-c-no"
            size="normal"
            shape="circle"
          />
          <!-- who posted? -->
          <span class="relative tracking-tight text-xs text-primary"
            >Halil Durak</span
          >
        </div>

        <!-- date -->
        <span class="relative tracking-tight text-xs text-surface-400"
          >3 gün önce</span
        >
      </div>
    </div>

    <hr class="relative border-surface-200" />

    <!-- About the job -->
    <div class="px-4 text-sm text-surface-800">
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maiores error
      itaque nihil, officiis odio eveniet, distinctio aliquam placeat neque
      voluptate hic repellat voluptatem laudantium sed delectus provident autem,
      fugiat dolor.
    </div>

    <!-- Footer -->
    <div class="relative bg-surface-50 py-3 px-4 w-full">
      <!-- Contact info -->
      <div class="flex flex-row items-center justify-between">
        <!-- Mail info -->
        <div
          class="relative flex flex-row items-center justify-start gap-x-1.5"
        >
          <PhosphorIconAt class="text-surface-400" :size="20" />
          <span class="text-xs text-surface-500">halildrk@gmail.com</span>
        </div>

        <!-- job detail icons -->
        <div class="relative flex flex-row gap-x-1.5">
          <PhosphorIconGlobe class="text-blue-500" :size="20" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.avatar {
  --p-avatar-width: 20px;
  --p-avatar-height: 20px;
}
</style>

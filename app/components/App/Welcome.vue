<script setup lang="ts"></script>

<template>
  <div class="flex h-screen flex-col items-center justify-center gap-6">
    <h1 class="text-(--ui-primary) text-6xl font-bold">Nuxt App</h1>

    <div class="flex w-80 gap-2">
      <div class="flex-1">
        <UButton
          label="Documentation"
          icon="i-lucide-square-play"
          to="https://ui4.nuxt.com/docs/getting-started/installation/nuxt"
          target="_blank"
          class="flex w-full items-center justify-center"
        />
      </div>

      <div class="flex-1">
        <UButton
          label="GitHub"
          color="neutral"
          variant="outline"
          icon="i-simple-icons-github"
          to="https://github.com/nuxt/ui"
          target="_blank"
          class="flex w-full items-center justify-center"
        />
      </div>
    </div>

    <UColorModeButton>
      <template #fallback>
        <UButton loading variant="ghost" color="neutral" />
      </template>
    </UColorModeButton>
  </div>
</template>

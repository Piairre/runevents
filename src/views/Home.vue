<template>
  <div class="flex items-center justify-center h-screen flex-col">
    <div class="text-center text-2xl">
      <h1>Run Events</h1>
    </div>
    <span>View all running events in your area</span>
    <RouterLink to="/sign-in" class="block mt-4">
      <Button>Sign In</Button>
    </RouterLink>
  </div>
</template>

<script setup lang="ts">
  import {Button} from "@/components/ui/button";
</script>
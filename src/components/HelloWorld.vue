<template>
  <div class="flex items-center justify-center h-screen flex-col">
    <div class="text-center text-2xl">
      <h1>{{ msg }}</h1>
    </div>
    <Button class="block mt-4">Shadcn Button</Button>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Button } from "@/components/ui/button";

export default defineComponent({
  name: "HelloWorld",
  components: { Button },
  props: {
    msg: String,
  },
});
</script>

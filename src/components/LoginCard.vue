<template>
  <div class="flex items-center justify-center min-h-screen bg-gray-100 p-4">
    <div class="w-full max-w-7xl p-8 bg-white rounded-xl shadow-md">
      <h2 class="text-3xl font-bold text-center text-gray-900 mb-8">Connexion</h2>
      <div class="flex flex-col md:flex-row gap-8">
        <!-- Colonne de gauche -->
        <div class="flex-1 space-y-6">
          <form class="space-y-4">
            <div>
              <label for="email" class="block text-sm font-medium text-gray-700">Adresse e-mail</label>
              <input id="email" name="email" type="email" required class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm placeholder-gray-400 focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
            </div>
            <div>
              <label for="password" class="block text-sm font-medium text-gray-700">Mot de passe</label>
              <input id="password" name="password" type="password" required class="mt-1 block w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm placeholder-gray-400 focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm">
            </div>
            <Button class="w-full" variant="default">Se connecter</Button>
          </form>
          <Button class="w-full" variant="outline">S'enregistrer</Button>
        </div>

        <div class="flex-1 space-y-6">
          <div class="text-center text-sm text-gray-600 mb-4">Ou se connecter avec</div>
          <div class="flex justify-center space-x-4">
            <Button variant="outline" size="icon" class="rounded-full w-12 h-12">
              Facebook
            </Button>
            <Button variant="outline" size="icon" class="rounded-full w-12 h-12">
              Google
            </Button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
  import { Button } from '@/components/ui/button'
</script>
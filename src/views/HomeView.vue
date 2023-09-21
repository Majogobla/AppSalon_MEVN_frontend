<script setup>
  
</script>

<template>
  <main>
    <h1 class="text-3xl text-white font-black text-center my-10">AppSalon - MEVN</h1>
    <p class="text-center text-white text-lg font-bold">
      Bienvenido a nuestra app, acá podrás agendar citas, registrarte para agendar una en el siguiente enlace
    </p>

    <div class="w-full flex justify-center">
      <RouterLink 
        :to="{name: 'register'}"
        class="text-white inline-block bg-green-700 p-4 my-5 text-center rounded-lg uppercase font-black hover:bg-green-900 transition-colors"
      >
        Crear Cuenta
      </RouterLink>
    </div>

    <p class="text-center text-white text-lg font-bold mt-10">
      ¿Ya posees una cuenta? Inicia Sesión
    </p>

    <div class="w-full flex justify-center">
      <RouterLink 
        :to="{name: 'login'}"
        class="text-white inline-block bg-blue-700 p-4 my-5 text-center rounded-lg uppercase font-black hover:bg-blue-900 transition-colors"
      >
        Iniciar Sesión
      </RouterLink>
    </div>
  </main>
</template>

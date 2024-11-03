<template>
  <div class="bg-slate-200">
    <NuxtLayout>
      <header>
        <ul>
          <NuxtLink to="/">Home</NuxtLink>
          <NuxtLink to="/events" class="mx-2">events</NuxtLink>
        </ul>
      </header>

      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

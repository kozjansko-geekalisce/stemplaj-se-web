<template>
  <div class="min-h-full">
    <nav class="bg-gray-800">
      <div class="mx-auto px-8">
        <div class="flex h-16 items-center justify-between">
          <img
            src="/images/logo.svg"
            class="h-14 invert"
            alt="Stemplaj se logo"
          />
        </div>
      </div>
    </nav>

    <main>
      <div class="mx-auto py-6 px-8">
        <slot />
      </div>
    </main>
  </div>
</template>

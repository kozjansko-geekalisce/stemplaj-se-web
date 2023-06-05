<template>
  <div
    class="flex min-h-screen bg-gray-800 flex-col justify-center px-6"
  >
    <div>
      <img
        src="/images/logo.svg"
        class="mx-auto h-28 invert"
        alt="Stemplaj se logo"
      />
    </div>

    <div class="mt-4 sm:mx-auto sm:w-full sm:max-w-sm text-white">
      <slot />
    </div>
  </div>
</template>

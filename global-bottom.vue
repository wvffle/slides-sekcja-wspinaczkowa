<template>
  <footer
    v-if="$nav.currentLayout !== 'cover'"
    class="absolute right-0 bottom-0 left-0 p-2"
  >
    {{ $nav.currentPage }} / {{ $nav.total }}
  </footer>
</template>

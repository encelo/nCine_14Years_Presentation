<!-- an example footer for pages -->
<template>
  <footer
    v-if="$nav.currentLayout !== 'cover'"
    class="absolute top-0 right-0 p-2"
  >
    {{ $nav.currentPage }} / {{ $nav.total }}
  </footer>
  <footer
    v-if="$nav.currentLayout !== 'cover'"
    class="absolute bottom-0 right-0 p-2"
  >
    <span class="text-xs"><a href="https://devgames.org/en/2025.html"><carbon-group-presentation /> /dev/games/2025</a></span>
  </footer>
</template>


<template>
<footer
   class="absolute bottom-5 left-93%
   right-0 p-2"
   v-if="$nav.currentPage !== 1 && $nav.currentPage !== 2"
   >
<Link to="2">
   <div class="i-carbon:home"/>
</Link>
</footer>
</template>

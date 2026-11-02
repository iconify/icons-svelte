<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x7zdd9sig"/><path class="ks8suqbtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-libra-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ks8suqbtn) {
  d: path("M7.16 16a7.71 7.71 0 1 1 9.68 0H20a1 1 0 0 1 0 2h-5a1 1 0 0 1-1-1v-1c0-.379.214-.725.553-.894a5.7 5.7 0 0 0 1.483-1.07a5.708 5.708 0 1 0-6.589 1.07A1 1 0 0 1 10 16v1a1 1 0 0 1-1 1H4a1 1 0 0 1 0-2Z");
}

:global(.x7zdd9sig) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 20h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="goeug6bgp"/><path class="rpqdc7f6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:smiley-angry-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.goeug6bgp) {
  d: path("M224 128a96 96 0 1 1-96-96a96 96 0 0 1 96 96");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rpqdc7f6w) {
  d: path("M92 152a12 12 0 1 1 12-12a12 12 0 0 1-12 12m72-24a12 12 0 1 0 12 12a12 12 0 0 0-12-12m68 0A104 104 0 1 1 128 24a104.11 104.11 0 0 1 104 104m-16 0a88 88 0 1 0-88 88a88.1 88.1 0 0 0 88-88m-44.44-46.66L128 110.39l-43.56-29a8 8 0 1 0-8.88 13.32l48 32a8 8 0 0 0 8.88 0l48-32a8 8 0 0 0-8.88-13.32Zm-15.13 96C148 171.73 139.94 168 128 168s-20 3.73-28.43 9.34a8 8 0 0 0 8.86 13.32C114.93 186.34 120 184 128 184s13.07 2.34 19.57 6.66a8 8 0 1 0 8.86-13.32");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6w3g-bwf"/><path class="uokof-bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-skip-previous" {...props}></Icon>
<style>
:global(.n6w3g-bwf) {
  fill: currentColor;
  d: path("M16 14.14V9.86L12.97 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.uokof-bnh) {
  fill: currentColor;
  d: path("M6 6h2v12H6zm12 12V6l-8.5 6zm-2-3.86L12.97 12L16 9.86z");
}

</style>

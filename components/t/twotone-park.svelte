<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-_-r_b9l"/><path class="f-1v_4bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-park" {...props}></Icon>
<style>
:global(.f-1v_4bkn) {
  fill: currentColor;
  d: path("M17 12h2L12 2L5.05 12H7l-3.9 6h6.92v4h3.95v-4H21zM6.79 16l3.9-6H8.88l3.13-4.5l3.15 4.5h-1.9l4 6z");
}

:global(.l-_-r_b9l) {
  fill: currentColor;
  d: path("M13.26 10h1.9l-3.15-4.5L8.88 10h1.81l-3.9 6h10.47z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

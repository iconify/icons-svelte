<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnr9ew5nh"/><path class="mxh72sc9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-foundation" {...props}></Icon>
<style>
:global(.mxh72sc9t) {
  fill: currentColor;
  d: path("M19 12h3L12 3L2 12h3v3H3v2h2v3h2v-3h4v3h2v-3h4v3h2v-3h2v-2h-2zM7 15v-4.81l4-3.6V15zm6 0V6.59l4 3.6V15z");
}

:global(.pnr9ew5nh) {
  fill: currentColor;
  d: path("M7 15v-4.81l4-3.6V15zm6 0V6.59l4 3.6V15z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

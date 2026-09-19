<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if282hfyl"/><circle class="c1fbsr3we"/><path class="zwphq79-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-hdr-weak" {...props}></Icon>
<style>
:global(.c1fbsr3we) {
  cx: 5px;
  cy: 12px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.if282hfyl) {
  fill: currentColor;
  d: path("M17 6c-3.31 0-6 2.69-6 6s2.69 6 6 6s6-2.69 6-6s-2.69-6-6-6m0 10c-2.21 0-4-1.79-4-4s1.79-4 4-4s4 1.79 4 4s-1.79 4-4 4");
}

:global(.zwphq79-a) {
  fill: currentColor;
  d: path("M5 8c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4m0 6c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2");
}

</style>

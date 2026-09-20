<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zxu5b42ht"/><path class="q71ix4yfi"/><path class="um-4xc65y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:test-double-duotone-bold" {...props}></Icon>
<style>
:global(.q71ix4yfi) {
  d: path("m4 5 7 7 -7 7Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.um-4xc65y) {
  d: path("m12 5 7 7 -7 7");
}

:global(.zxu5b42ht) {
  fill: currentColor;
  d: path("m4 5 7 7 -7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

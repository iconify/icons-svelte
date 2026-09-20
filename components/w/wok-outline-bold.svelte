<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vt8fxebuz"/><path class="q3b6j7bvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wok-outline-bold" {...props}></Icon>
<style>
:global(.q3b6j7bvq) {
  d: path("M20 10c2 0 2 -4 -1 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vt8fxebuz) {
  d: path("M4 10h16l-6 6h-4Z");
}

</style>

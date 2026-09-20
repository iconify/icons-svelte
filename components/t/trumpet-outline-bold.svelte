<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="akyaa-boy"/><path class="nuk2gwb4b"/><path class="gstzuxb9r"/><path class="ldq326b0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trumpet-outline-bold" {...props}></Icon>
<style>
:global(.akyaa-boy) {
  d: path("M13 11H2v4h11");
}

:global(.gstzuxb9r) {
  d: path("M5 7v4");
}

:global(.ldq326b0y) {
  d: path("M9 7v4");
}

:global(.nuk2gwb4b) {
  d: path("m13 9 6 -6v18l-6 -6Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

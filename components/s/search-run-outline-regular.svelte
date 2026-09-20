<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t9l7d0eki"/><path class="i6lzm3bun"/><path class="awo9bn4mw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:search-run-outline-regular" {...props}></Icon>
<style>
:global(.awo9bn4mw) {
  d: path("M16 8v8l4 -4Z");
}

:global(.i6lzm3bun) {
  d: path("M5.5 13 3 15.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t9l7d0eki) {
  d: path("M4 10a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

</style>

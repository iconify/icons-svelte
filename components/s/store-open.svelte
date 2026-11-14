<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hr04v9bok"/><path class="ymo_d4btp"/><path class="mdmxi1yng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:store-open" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hr04v9bok) {
  d: path("m3 6.5l1.5-4h15l1.5 4M4.5 9v12.5h15V9");
}

:global(.mdmxi1yng) {
  fill: currentColor;
  d: path("M11.5 15h1a1.5 1.5 0 0 1 1.5 1.5v.25a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-.25a1.5 1.5 0 0 1 1.5-1.5");
}

:global(.ymo_d4btp) {
  d: path("M3 6.5a3 3 0 0 0 6 0a3 3 0 0 0 6 0a3 3 0 0 0 6 0m-13.75 15v-9.25h9.5v9.25");
}

</style>

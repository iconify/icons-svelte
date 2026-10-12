<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u6ie11bfa"/><path class="rk7rft3-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:white-hat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rk7rft3-j) {
  d: path("M6.25 8.25C10 9 14 9 17.75 8.25M8.5 18.5L11 21l4.75-4.75");
}

:global(.u6ie11bfa) {
  d: path("M2.75 11.75c0-.8 1.6-1.4 3.5-1.65V6.75c0-2.2 2.3-4 5.75-4s5.75 1.8 5.75 4v3.35c1.9.25 3.5.85 3.5 1.65c0 1.1-4.15 2-9.25 2s-9.25-.9-9.25-2");
}

</style>

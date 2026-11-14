<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vslo0jbmz"/><path class="u05lib6pa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:security-tag-hard" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u05lib6pa) {
  d: path("M9.75 14a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M12 2.5v9.25");
}

:global(.vslo0jbmz) {
  d: path("M4.5 14a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0m-2-9C6 3.5 9 6.5 12 5s6 1.5 9.5 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cn-n_sbil"/><path class="gh1wydxtv"/><path class="v-5jk5fge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wrestling-headgear" {...props}></Icon>
<style>
:global(.cn-n_sbil) {
  d: path("M5 11a7 7 0 0 1 14 0");
}

:global(.gh1wydxtv) {
  d: path("M2.5 15.25a2.5 4.25 0 1 0 5 0a2.5 4.25 0 1 0-5 0Zm14 0a2.5 4.25 0 1 0 5 0a2.5 4.25 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v-5jk5fge) {
  d: path("M5 19.5q7 3.5 14 0");
}

</style>

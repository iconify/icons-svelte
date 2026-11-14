<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aipfl-vgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vision-benefit" {...props}></Icon>
<style>
:global(.aipfl-vgz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m11 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-3-.5c.75-1 2.25-1 3 0m-11 .5L4 8m17.5 5.5L20 8");
}

</style>

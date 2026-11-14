<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsp2_zbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thermometer" {...props}></Icon>
<style>
:global(.nsp2_zbup) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14V5.5a2 2 0 0 1 4 0V14a4 4 0 1 1-4 0m7-7.5h2m-2 3h2m-2 3h2");
}

</style>

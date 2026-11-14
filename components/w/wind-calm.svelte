<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8-5mab1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wind-calm" {...props}></Icon>
<style>
:global(.t8-5mab1v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5v19M10 4h7v11q-3.5-1.5-7 1m-3.5 5.5h7m0-15V12");
}

</style>

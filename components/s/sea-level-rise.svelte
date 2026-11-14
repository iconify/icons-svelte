<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvo00ibyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sea-level-rise" {...props}></Icon>
<style>
:global(.cvo00ibyb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11Q4.75 9 7 11t4.5 0t4.5 0M2.5 18q2.25-2 4.5 0t4.5 0t4.5 0m3 1V4.5m-2.75 2.75L19 4.5l2.75 2.75");
}

</style>

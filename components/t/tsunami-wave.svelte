<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2yxicc5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tsunami-wave" {...props}></Icon>
<style>
:global(.s2yxicc5b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c3.5 0 5.5-5 6-9c1-7 7.5-8.5 11-5.5c2 2 1 5.5-2 5.5c-2 0-2.5-2-1.5-3M2.5 20h12m0 0l7-5");
}

</style>

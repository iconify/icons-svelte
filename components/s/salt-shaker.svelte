<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3g512b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:salt-shaker" {...props}></Icon>
<style>
:global(.j3g512b-i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9h10l-.5 11h-9Zm1 0c0-4 1.5-5.5 4-5.5S16 5 16 9m-5.5-2.5h.01m2.99 0h.01");
}

</style>

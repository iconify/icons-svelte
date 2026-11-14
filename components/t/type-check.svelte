<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnavx7qop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:type-check" {...props}></Icon>
<style>
:global(.fnavx7qop) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4h15M11 4v16m3.75-2l2 2L21 15.75");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe2guabgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:swap-vertical" {...props}></Icon>
<style>
:global(.fe2guabgv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4.25v15.5m-3.5-3.5l3.5 3.5l3.5-3.5m5 3.5V4.25m-3.5 3.5l3.5-3.5l3.5 3.5");
}

</style>

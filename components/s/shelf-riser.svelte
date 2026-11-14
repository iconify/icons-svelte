<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9o51lbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shelf-riser" {...props}></Icon>
<style>
:global(.p9o51lbwh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5V13H11V5h10.5v16.5ZM11 13v8.5m-6-4.25h3.5m5-4H19");
}

</style>

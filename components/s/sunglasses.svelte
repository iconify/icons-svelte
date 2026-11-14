<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkcqbg78e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sunglasses" {...props}></Icon>
<style>
:global(.qkcqbg78e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h18M6.25 9h1A2.75 2.75 0 0 1 10 11.75a2.75 2.75 0 0 1-2.75 2.75h-1a2.75 2.75 0 0 1-2.75-2.75A2.75 2.75 0 0 1 6.25 9m10.5 0h1a2.75 2.75 0 0 1 2.75 2.75a2.75 2.75 0 0 1-2.75 2.75h-1A2.75 2.75 0 0 1 14 11.75A2.75 2.75 0 0 1 16.75 9M10 11h4");
}

</style>

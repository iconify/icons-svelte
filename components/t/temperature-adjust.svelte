<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqhtirb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:temperature-adjust" {...props}></Icon>
<style>
:global(.wqhtirb2l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 14V5a2.5 2.5 0 0 1 5 0v9a4 4 0 1 1-5 0m8-8h3m-3 4h3");
}

</style>

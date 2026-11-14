<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2aq6eb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sigma-sum" {...props}></Icon>
<style>
:global(.a2aq6eb8w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 5H6l6.5 7L6 19h12.5");
}

</style>

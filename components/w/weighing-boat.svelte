<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l122ce_yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:weighing-boat" {...props}></Icon>
<style>
:global(.l122ce_yg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19m-17 0l2.75 8h9.5l2.75-8");
}

</style>

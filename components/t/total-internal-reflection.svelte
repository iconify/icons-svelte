<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajufy0bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:total-internal-reflection" {...props}></Icon>
<style>
:global(.ajufy0bcq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19m-19 11h19M2.5 12l4-5.5l6.5 11l6.5-11l2 3");
}

</style>

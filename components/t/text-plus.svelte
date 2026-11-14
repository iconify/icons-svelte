<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo15fobke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:text-plus" {...props}></Icon>
<style>
:global(.uo15fobke) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5h17m-17 5h17m-17 5h8m-8 5h8m6.5-5v6m-3-3h6");
}

</style>

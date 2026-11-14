<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i24qavkbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:washing-up-bowl" {...props}></Icon>
<style>
:global(.i24qavkbg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18a9 9 0 0 1-18 0m4 0a2.5 2.5 0 0 1 3-3.5a3 3 0 0 1 5.5-.5a2.5 2.5 0 0 1 1.5 4");
}

</style>

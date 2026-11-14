<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_slwbb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:slash-forward" {...props}></Icon>
<style>
:global(.f_slwbb0u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.5 2.5l-9 19");
}

</style>

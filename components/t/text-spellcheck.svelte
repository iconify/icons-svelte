<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_2q3cbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:text-spellcheck" {...props}></Icon>
<style>
:global(.s_2q3cbkz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14L7.5 3.5L12 14m-7.25-4h5.5m.75 7.5l3 3l7-7");
}

</style>

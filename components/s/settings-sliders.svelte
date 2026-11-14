<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxdqq5btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:settings-sliders" {...props}></Icon>
<style>
:global(.xxdqq5btv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3v9.75m0 4.5V21m6-18v2.75m0 4.5V21m6-18v7.75m0 4.5V21M3.75 15a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6-7a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>

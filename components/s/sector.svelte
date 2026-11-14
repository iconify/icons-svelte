<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3t-9q85x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sector" {...props}></Icon>
<style>
:global(.p3t-9q85x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 19.5v-15a15 15 0 0 1 15 15Z");
}

</style>

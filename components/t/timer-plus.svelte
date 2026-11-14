<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx19ksb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:timer-plus" {...props}></Icon>
<style>
:global(.xx19ksb6d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0M9.5 2.5h5m-2.5 7v7M8.5 13h7");
}

</style>

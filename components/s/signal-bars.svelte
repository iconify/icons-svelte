<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nod6vjs2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:signal-bars" {...props}></Icon>
<style>
:global(.nod6vjs2u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18.5v-3m4.5 3v-6m4.5 6V9m4.5 9.5v-13");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlelcvbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:workbench" {...props}></Icon>
<style>
:global(.nlelcvbxb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 12H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 9m1 3v9m14-9v9M5 17.5h14M16 5h1.5A1.5 1.5 0 0 1 19 6.5v1A1.5 1.5 0 0 1 17.5 9H16a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 16 5M6 6h5");
}

</style>

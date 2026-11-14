<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydl7a3bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:share-up" {...props}></Icon>
<style>
:global(.ydl7a3bzr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14.5v6h16v-6m-8-12V16M7.5 7L12 2.5L16.5 7");
}

</style>

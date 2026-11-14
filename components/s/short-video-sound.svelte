<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ts2sk6udc"/><path class="w7vheccco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:short-video-sound" {...props}></Icon>
<style>
:global(.ts2sk6udc) {
  d: path("M14.9 15.5H2.5V3h17v8.2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w7vheccco) {
  d: path("m9 5.75l6 3.5l-6 3.5ZM14.25 20a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0v-6.5l3.5 1.25");
}

</style>

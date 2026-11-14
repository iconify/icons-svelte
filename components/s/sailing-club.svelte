<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="irdj4ac9c"/><path class="febfkcgtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sailing-club" {...props}></Icon>
<style>
:global(.febfkcgtn) {
  d: path("M7.5 21.5v-4h3v4");
}

:global(.irdj4ac9c) {
  d: path("M3.5 13L9 7.5l5.5 5.5v8.5h-11Zm16-10.5v19m0-18.75l-5 2.5l5 2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="liukvs2qv"/><path class="evelys07t"/><path class="i2-ny_bzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stop-line" {...props}></Icon>
<style>
:global(.evelys07t) {
  fill: currentColor;
  d: path("M5.75 11.5h12.5v3H5.75Z");
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.liukvs2qv) {
  d: path("M3 2.5v19m18-19v19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

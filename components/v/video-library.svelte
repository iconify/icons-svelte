<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jcx262x8m"/><path class="v_pehibsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:video-library" {...props}></Icon>
<style>
:global(.jcx262x8m) {
  d: path("M9.5 2.5h12v19h-12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_pehibsy) {
  d: path("m13.5 8.5l5 3.5l-5 3.5ZM3 5.5v16m3.5-18v18");
}

</style>

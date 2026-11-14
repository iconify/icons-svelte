<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v7yd27b-i"/><path class="mw3g3kvga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:u-turn-right" {...props}></Icon>
<style>
:global(.mw3g3kvga) {
  d: path("m13.5 13l3 3l3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v7yd27b-i) {
  d: path("M6.5 20V10a5 5 0 0 1 10 0v6");
}

</style>

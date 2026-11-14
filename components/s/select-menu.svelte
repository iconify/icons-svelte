<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tnvl6hbxj"/><path class="stw4lhbvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:select-menu" {...props}></Icon>
<style>
:global(.stw4lhbvt) {
  d: path("m13.5 10.75l2.5 2.5l2.5-2.5");
}

:global(.tnvl6hbxj) {
  d: path("M2.5 6h19v12h-19ZM6 12h3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

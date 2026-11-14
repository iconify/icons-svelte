<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xv5eb7bgy"/><path class="m7av8glcy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skier-fall" {...props}></Icon>
<style>
:global(.m7av8glcy) {
  d: path("M3.691 17.834L17.834 3.691l2.475 2.475L6.166 20.309Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xv5eb7bgy) {
  d: path("m6.166 3.691l14.143 14.143l-2.475 2.475L3.691 6.166Z");
}

</style>

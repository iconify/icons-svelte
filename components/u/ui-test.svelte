<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o5bvvkbot"/><path class="u6v1tzb-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ui-test" {...props}></Icon>
<style>
:global(.o5bvvkbot) {
  d: path("M12.5 18h-10V3h19v9.1m0 5.3v.6h-1.3");
}

:global(.u6v1tzb-n) {
  d: path("M9.8 9.5H5.5V6h7v2.6m1 3.4l7 2.75l-3 1.5l-1.5 3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

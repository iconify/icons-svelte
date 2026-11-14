<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xklv2yp2t"/><path class="ew-6rkhav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:smart-switch-on" {...props}></Icon>
<style>
:global(.ew-6rkhav) {
  d: path("M7.5 5.5h6V15h-6Zm0 3.25h6M14.75 18l2 2L21 15.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xklv2yp2t) {
  d: path("M13.8 21H3V2.5h15v12.3");
}

</style>

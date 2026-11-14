<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ixzx_qbdt"/><path class="vbkq21fej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:table-cells-merge" {...props}></Icon>
<style>
:global(.ixzx_qbdt) {
  d: path("M2.5 5h19v14h-19Zm3 7h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vbkq21fej) {
  d: path("m7.5 10l2 2l-2 2m11-2h-4m2-2l-2 2l2 2");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g7fykeuht"/><path class="qkcf50atv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:torque" {...props}></Icon>
<style>
:global(.g7fykeuht) {
  d: path("M16.75 7.25a3 3 0 1 1-2-2.25m-3 5.25L3.5 18.5m17-6.75a7.5 7.5 0 0 1-7.75 3.75");
}

:global(.qkcf50atv) {
  d: path("m14.5 13.75l-1.75 1.75l2 1.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

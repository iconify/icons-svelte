<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fud-zw_3g"/><path class="k-luzcczh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:turn-left-then-right" {...props}></Icon>
<style>
:global(.fud-zw_3g) {
  d: path("M15 21v-4.5a2 2 0 0 0-2-2H7a2 2 0 0 1-2-2V8.75a2 2 0 0 1 2-2h12.5");
}

:global(.k-luzcczh) {
  d: path("m16.75 4l2.75 2.75l-2.75 2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

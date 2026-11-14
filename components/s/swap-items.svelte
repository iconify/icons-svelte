<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kxll9fbsc"/><path class="baiv3ne2o"/><path class="f8vpl2bor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:swap-items" {...props}></Icon>
<style>
:global(.baiv3ne2o) {
  d: path("m16.5 8l2 2l2-2M10 18.5H8.5a3 3 0 0 1-3-3V14");
}

:global(.f8vpl2bor) {
  d: path("m3.5 16l2-2l2 2");
}

:global(.kxll9fbsc) {
  d: path("M3.5 3.5h7v7h-7Zm10 10h7v7h-7Zm.5-8h1.5a3 3 0 0 1 3 3V10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fmshjwb_n"/><path class="rkfq4ab9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trombone-sharp" {...props}></Icon>
<style>
:global(.fmshjwb_n) {
  d: path("m3.62 4.25l3.51 2l.87.5v1.5l-.87.5l-3.51 2l-.87.5v-7.5z");
}

:global(.rkfq4ab9p) {
  d: path("M8 7.5h13.25V15H8.5a2.75 2.75 0 0 0 0 5.5h12.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

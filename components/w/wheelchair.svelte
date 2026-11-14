<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v7jjuqfnq"/><path class="jtegwwo-n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wheelchair" {...props}></Icon>
<style>
:global(.jtegwwo-n) {
  d: path("M14.505 12.345a5.5 5.5 0 1 1-9.01 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v7jjuqfnq) {
  d: path("M8 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM10 8v4.5h5.5l2.5 7");
}

</style>

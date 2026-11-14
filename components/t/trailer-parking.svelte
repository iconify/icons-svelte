<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hz51vnb5y"/><path class="ujf638e5v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trailer-parking" {...props}></Icon>
<style>
:global(.hz51vnb5y) {
  d: path("M3.5 4.5h17v15h-17Z");
}

:global(.ujf638e5v) {
  d: path("M9 16.5V8h3.5a2.5 2.5 0 0 1 0 5H9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cah_lcc8z"/><path class="j39k94b3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stock-adjustment" {...props}></Icon>
<style>
:global(.cah_lcc8z) {
  d: path("M12.738 21.131L12 21.5L3 17V7l9-4.5L21 7v6.438");
}

:global(.j39k94b3q) {
  d: path("m3 7l9 4.5L21 7m-9 4.5v10M7.5 4.75l9 4.5m1.5 5v4m-2-2h4M15.5 21h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

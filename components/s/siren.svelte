<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n-o48ubkn"/><path class="i09avnb_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:siren" {...props}></Icon>
<style>
:global(.i09avnb_o) {
  d: path("M9.5 13a2.5 2.5 0 0 1 2.5-2.5m0-8v2M3.5 6L5 7.5M20.5 6L19 7.5");
}

:global(.n-o48ubkn) {
  d: path("M6.5 17.5V13a5.5 5.5 0 0 1 11 0v4.5M4 17.5h16V21H4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="un5_dc36f"/><path class="t_xl2cbry"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tax-scales" {...props}></Icon>
<style>
:global(.t_xl2cbry) {
  d: path("M16.5 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.un5_dc36f) {
  d: path("M12 3v17.5m-4.5 0h9M5.5 13V6.5h13V9M2 13h7a3.5 3.5 0 0 1-7 0Zm13 0h7a3.5 3.5 0 0 1-7 0Z");
}

</style>

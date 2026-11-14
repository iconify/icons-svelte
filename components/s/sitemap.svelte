<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qhzkoqbno"/><path class="vclzaqops"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sitemap" {...props}></Icon>
<style>
:global(.qhzkoqbno) {
  d: path("M9 3h6v5H9ZM2.5 16h5v5h-5Zm7 0h5v5h-5Zm7 0h5v5h-5ZM12 8v8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vclzaqops) {
  d: path("M5 16v-2a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 19 14v2");
}

</style>

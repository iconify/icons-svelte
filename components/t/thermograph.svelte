<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vuaw5focb"/><path class="egjaj_btr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:thermograph" {...props}></Icon>
<style>
:global(.egjaj_btr) {
  d: path("m6.75 15l1.5-3.75l1.5 3.25l1.5-4m0 0l7.25-2.25m0-.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vuaw5focb) {
  d: path("M2.5 3h13v3.5h-13ZM4 6.5v14h10v-14");
}

</style>

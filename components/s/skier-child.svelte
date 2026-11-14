<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f6cl3mbpq"/><path class="p87ht-f4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skier-child" {...props}></Icon>
<style>
:global(.f6cl3mbpq) {
  d: path("M3.5 15v-4.5a5 5 0 0 1 10 0V12h-4v3");
}

:global(.p87ht-f4a) {
  d: path("M2.5 15H16c2.5 0 3.5-1.5 4-3.5m-16 7h13.5c2.5 0 3.5-1.5 4-3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

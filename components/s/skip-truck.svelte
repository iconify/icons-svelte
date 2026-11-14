<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pqbqubb7o"/><path class="eu2-dbvoj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skip-truck" {...props}></Icon>
<style>
:global(.eu2-dbvoj) {
  d: path("M16 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM2.5 6.5h10l-1.5 10H4Z");
}

:global(.pqbqubb7o) {
  d: path("M15 16.5V9h3.5l3 3.5v4m-19 0h19M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

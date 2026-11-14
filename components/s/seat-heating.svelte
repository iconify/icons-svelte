<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m-hp0e4te"/><path class="ab8ehjhiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:seat-heating" {...props}></Icon>
<style>
:global(.ab8ehjhiv) {
  d: path("M12 4c-.75 1 .75 2 0 3s.75 2 0 3m3.25-6c-.75 1 .75 2 0 3s.75 2 0 3m3.25-6c-.75 1 .75 2 0 3s.75 2 0 3");
}

:global(.m-hp0e4te) {
  d: path("M4.5 4.75c0-1 .75-1.75 1.75-1.5l1 .25C8 3.75 8.5 4.25 8.5 5l.5 7.75h6c1.25 0 2 .75 2 2s-.75 2-2 2H7.5q-1.5 0-1.5-1.5Zm4.5 12v3.75m-3 0h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

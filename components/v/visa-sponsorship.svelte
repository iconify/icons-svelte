<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ekf2s55jf"/><path class="t1mye8pat"/><path class="sndhr7bpl"/><path class="fyxw6hb7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:visa-sponsorship" {...props}></Icon>
<style>
:global(.ekf2s55jf) {
  d: path("M2.5 15H6l4 2.5h4.25a1.25 1.25 0 0 1 0 2.5H9.5");
}

:global(.fyxw6hb7e) {
  d: path("M11.5 6.5a1 2.25 0 1 0 2 0a1 2.25 0 1 0-2 0Zm-1.25 0h4.5m-4.5 4.5h4.5");
}

:global(.sndhr7bpl) {
  d: path("M10.25 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

:global(.t1mye8pat) {
  d: path("M2.5 21.5H13l7.25-4.75c1-.75.25-2.25-1-1.75l-3.75 2.5M8 2h9v11H8Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

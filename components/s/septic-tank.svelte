<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ms7_b19kg"/><path class="nzrn7sb2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:septic-tank" {...props}></Icon>
<style>
:global(.ms7_b19kg) {
  d: path("M4 11.5h16a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-7.5a1 1 0 0 1 1-1Zm-1.5-5h9m4-4v9m-2-9h4");
}

:global(.nzrn7sb2l) {
  d: path("M5.5 16q3-1.5 6 0c2 1 4 1 7 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

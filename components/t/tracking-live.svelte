<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p74nhaccs"/><path class="nke9ovbpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tracking-live" {...props}></Icon>
<style>
:global(.nke9ovbpb) {
  d: path("M5.5 5.5a9 9 0 0 0 0 13m13-13a9 9 0 0 1 0 13");
}

:global(.p74nhaccs) {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM7.5 7.5a6.5 6.5 0 0 0 0 9m9-9a6.5 6.5 0 0 1 0 9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

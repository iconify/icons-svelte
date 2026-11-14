<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xzcbvbbta"/><path class="vcoi6eblj"/><path class="owm-v3b9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-polo-ball" {...props}></Icon>
<style>
:global(.owm-v3b9w) {
  d: path("M12 2.5q-3 7 0 14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vcoi6eblj) {
  d: path("M5.5 7q6.5 4 13 0");
}

:global(.xzcbvbbta) {
  d: path("M5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm-2 11q2.25-1.75 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>

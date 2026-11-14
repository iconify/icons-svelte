<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="afwirynja"/><path class="qz_72actf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shop-window-display" {...props}></Icon>
<style>
:global(.afwirynja) {
  d: path("M3.5 2.5h17V19h-17ZM2.5 19h19");
}

:global(.qz_72actf) {
  d: path("M10.25 6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-2 4.5c0-1.25 1.25-1.75 3.75-1.75s3.75.5 3.75 1.75c-.5 1.5-1.75 2-1.75 4h-4c0-2-1.25-2.5-1.75-4Zm3.75 4v2.25m-2 0h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iwxixcb3y"/><path class="mcoaarhzv"/><path class="e2h5sfmdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tennis-ball-can" {...props}></Icon>
<style>
:global(.e2h5sfmdq) {
  d: path("M5.5 13.5a6.5 2 0 0 0 13 0");
}

:global(.iwxixcb3y) {
  d: path("M5.5 8a6.5 2 0 1 0 13 0a6.5 2 0 1 0-13 0Z");
}

:global(.mcoaarhzv) {
  d: path("M5.5 8v11.5a6.5 2 0 0 0 13 0V8M7 6.75A2.75 2.75 0 0 1 12 6a2.75 2.75 0 0 1 5 .75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

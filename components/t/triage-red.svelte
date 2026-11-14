<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eeelanbur"/><path class="p56k60bao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:triage-red" {...props}></Icon>
<style>
:global(.eeelanbur) {
  d: path("m12 4l5.5 4v11.5c0 1.1-.9 2-2 2h-7c-1.1 0-2-.9-2-2V8Zm0 4l4-5.5");
}

:global(.p56k60bao) {
  d: path("M10.75 8a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm-.25 4.75l1.75-1.25v7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

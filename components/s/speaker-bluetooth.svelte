<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0f-lgkcm"/><path class="dhgngdcdy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:speaker-bluetooth" {...props}></Icon>
<style>
:global(.dhgngdcdy) {
  d: path("M9 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm1.5-10.5l3 2.75l-1.5 1.5v-6l1.5 1.5l-3 2.75");
}

:global(.q0f-lgkcm) {
  d: path("M5 2.5h14v19H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

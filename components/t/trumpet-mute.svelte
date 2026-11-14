<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpb_occ7x"/><path class="pamquncuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trumpet-mute" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pamquncuc) {
  d: path("M7 17h10a2 2 0 0 1 2 2a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2a2 2 0 0 1 2-2m1.5-9h7");
}

:global(.rpb_occ7x) {
  d: path("M11.233 3h1.534a1.75 1.75 0 0 1 1.648 1.161l3.75 10.5A1.75 1.75 0 0 1 16.517 17H7.483a1.75 1.75 0 0 1-1.648-2.339l3.75-10.5A1.75 1.75 0 0 1 11.233 3");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kzc79nwkq"/><path class="wy0x8llmy"/><path class="sgyxn-zbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:writing-hand-sharp" {...props}></Icon>
<style>
:global(.kzc79nwkq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.55 11.3l1.15-1.85l1.05-1.7H18l1.41 1.41l.43.43L21.25 11v6.25H13.5l-1.37-1.46l-1.26-1.33L9.5 13zm4.95-.55h3.25m-3.5 2.75h3.5m-.09-10.1L16 7.75m-4.5 7.35l-1.3 2.13");
}

:global(.sgyxn-zbj) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 20H21");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.wy0x8llmy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 20h.01");
}

</style>

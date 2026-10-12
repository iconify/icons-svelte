<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="t2m-dwb6r"/><path class="tg88rjk5z"/><path class="a0g_eunes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:surge-protector-sharp" {...props}></Icon>
<style>
:global(.a0g_eunes) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 12h.01");
}

:global(.t2m-dwb6r) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.25h15v7.5h-15zm15 3.75h2.5v9.25");
}

:global(.tg88rjk5z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 10.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 1 1 0-3m4.5 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 1 1 0-3");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

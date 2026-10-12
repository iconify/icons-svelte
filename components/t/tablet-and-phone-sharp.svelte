<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pknexub1j"/><path class="nfvs04hze"/><path class="d2bjv9ehr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tablet-and-phone-sharp" {...props}></Icon>
<style>
:global(.d2bjv9ehr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 9.25h6v12h-6zm2.25 9.25H19");
}

:global(.nfvs04hze) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 18h.01");
}

:global(.pknexub1j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h12v3.5h-5.5v15h-8.5V2.75z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

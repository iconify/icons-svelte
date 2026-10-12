<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="z7fyc87xr"/><circle class="r0ew8gbrg"/><path class="fnrnvwv4f"/><circle class="riohgnbtm"/><path class="g27ahybtf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:safari-jeep-sharp" {...props}></Icon>
<style>
:global(.fnrnvwv4f) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 19h.01");
}

:global(.g27ahybtf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 19h.01");
}

:global(.r0ew8gbrg) {
  cx: 9.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.riohgnbtm) {
  cx: 17.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.z7fyc87xr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11V7h7v4m-8.75 4.75V11h9.75l.71.71l.08.08l.71.71h4.25v4.25H5.75z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o48nut9qz"/><path class="omcxz1ygw"/><path class="fti-unbge"/><path class="ry7zsib4b"/><path class="x2ha0bcpp"/><path class="hxeojfb0f"/><path class="uk0rveqaj"/><path class="rdx5t34om"/><path class="aq5i5tblx"/><path class="p83l94bht"/><path class="tk9h-knrv"/><path class="cp8xb3bty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:service-mesh-duotone-thin" {...props}></Icon>
<style>
:global(.aq5i5tblx) {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.cp8xb3bty) {
  d: path("m16 9 -8 8");
}

:global(.fti-unbge) {
  fill: currentColor;
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hxeojfb0f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 9 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o48nut9qz) {
  fill: currentColor;
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.omcxz1ygw) {
  fill: currentColor;
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.p83l94bht) {
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rdx5t34om) {
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ry7zsib4b) {
  fill: currentColor;
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tk9h-knrv) {
  d: path("m8 9 8 8");
}

:global(.uk0rveqaj) {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.x2ha0bcpp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 9 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

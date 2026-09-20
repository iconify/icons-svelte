<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="digwvcbca"/><path class="jn0zvwb6e"/><path class="wykgeg31p"/><path class="b6szz2b6j"/><path class="gar666bgi"/><path class="xgrfb-bqu"/><path class="d8abqfbpc"/><path class="k0js09kko"/><path class="qouhnhnfp"/><path class="t40-rxb9c"/><path class="elwkggrsn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-complete-duotone-regular" {...props}></Icon>
<style>
:global(.b6szz2b6j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 13.5 19 16l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.be306ynmy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.digwvcbca) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.elwkggrsn) {
  d: path("M22 13.5v5");
}

:global(.gar666bgi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M22 13.5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jn0zvwb6e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k0js09kko) {
  d: path("M3 16h9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qouhnhnfp) {
  d: path("M15 16h4");
}

:global(.t40-rxb9c) {
  d: path("M16.5 13.5 19 16l-2.5 2.5");
}

:global(.wykgeg31p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i7z0vob4i"/><path class="hmylfkbub"/><path class="q5fdyummg"/><path class="jp1ucxmwc"/><path class="vubu-cfsw"/><path class="xf07dvr8m"/><path class="tr_jskylo"/><path class="hxoe7gx5p"/><path class="e0001wg8c"/><path class="y_21nobec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:waterfall-duotone-regular" {...props}></Icon>
<style>
:global(.e0001wg8c) {
  d: path("M17 5v12");
}

:global(.hmylfkbub) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hxoe7gx5p) {
  d: path("M12 5v12");
}

:global(.i7z0vob4i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jp1ucxmwc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q5fdyummg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tr_jskylo) {
  d: path("M7 5v12");
}

:global(.vubu-cfsw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xf07dvr8m) {
  d: path("M2 5h20");
}

:global(.y_21nobec) {
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>

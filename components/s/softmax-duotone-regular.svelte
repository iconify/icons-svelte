<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pga6n1bci"/><path class="sbbpuub-h"/><path class="l--d5frob"/><path class="r8ufrvbbt"/><path class="ouw0zmbdc"/><path class="jkuojibnm"/><path class="d1du4rxru"/><path class="a9cczt5un"/><path class="t3w_facee"/><path class="j4if4rbfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:softmax-duotone-regular" {...props}></Icon>
<style>
:global(.a9cczt5un) {
  d: path("M10 8v12");
}

:global(.d1du4rxru) {
  d: path("M6 14v6");
}

:global(.j4if4rbfv) {
  d: path("M18 14v6");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.l--d5frob) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ouw0zmbdc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pga6n1bci) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r8ufrvbbt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 3v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sbbpuub-h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3w_facee) {
  d: path("M14 3v17");
}

</style>

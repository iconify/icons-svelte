<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="udw1i4tmx"/><path class="vhfnkdb-k"/><path class="vvz16lq6z"/><path class="jtrmczbpr"/><path class="n6amu-bmd"/><path class="n_hih6bwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stream-duotone-bold" {...props}></Icon>
<style>
:global(.jtrmczbpr) {
  d: path("M2 6h14");
}

:global(.n_hih6bwb) {
  d: path("M2 18h14");
}

:global(.n6amu-bmd) {
  d: path("M8 12h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.udw1i4tmx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vhfnkdb-k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vvz16lq6z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

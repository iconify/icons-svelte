<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mpmgljbgd"/><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="okds9dbso"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e_6o-gbms"/><path class="blo0wbrjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:target-line-duotone-bold" {...props}></Icon>
<style>
:global(.blo0wbrjk) {
  d: path("M11 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e_6o-gbms) {
  d: path("M6 10h13");
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mpmgljbgd) {
  fill: currentColor;
  d: path("M11 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.okds9dbso) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

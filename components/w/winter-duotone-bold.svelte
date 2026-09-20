<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vrymclvxs"/><path class="xaz90clio"/><path class="i-83p_bua"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:winter-duotone-bold" {...props}></Icon>
<style>
:global(.i-83p_bua) {
  d: path("M12 4v12m-6 0L18 4");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vrymclvxs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v12m-6 0L18 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xaz90clio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

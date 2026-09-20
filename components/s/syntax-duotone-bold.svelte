<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dhgggtb3s"/><path class="mvc_pjbyz"/><path class="rv1mb2bps"/><path class="mufl12bgg"/><path class="zaau21ski"/><path class="vj8si9dha"/><path class="fa2e7y2tg"/><path class="wfg0vmbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:syntax-duotone-bold" {...props}></Icon>
<style>
:global(.dhgggtb3s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4 4 8l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fa2e7y2tg) {
  d: path("M4 17h8");
}

:global(.mufl12bgg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 17h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mvc_pjbyz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 4 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rv1mb2bps) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vj8si9dha) {
  d: path("m16 4 4 4 -4 4");
}

:global(.wfg0vmbgy) {
  d: path("M15 17h5");
}

:global(.zaau21ski) {
  d: path("M8 4 4 8l4 4");
}

</style>

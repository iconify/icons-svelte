<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xfs8wlfhn"/><path class="iml3cbclx"/><path class="r9il7jbjw"/><path class="b2n99wbku"/><path class="q829csbzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:timing-attack-outline-bold" {...props}></Icon>
<style>
:global(.b2n99wbku) {
  d: path("M12 12.5v3");
}

:global(.iml3cbclx) {
  d: path("M8 7a4 4 0 0 1 8 0");
}

:global(.q829csbzu) {
  d: path("M12 15.5h2.5");
}

:global(.r9il7jbjw) {
  d: path("M9 15.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xfs8wlfhn) {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

</style>

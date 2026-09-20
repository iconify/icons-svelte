<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uweslxo3x"/><path class="cfd43lbgp"/><path class="p0hi_9aen"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-warning-outline-bold" {...props}></Icon>
<style>
:global(.cfd43lbgp) {
  d: path("M7 13h10");
}

:global(.p0hi_9aen) {
  d: path("M5 17h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uweslxo3x) {
  d: path("M12 3.5 21.5 20h-19Z");
}

</style>

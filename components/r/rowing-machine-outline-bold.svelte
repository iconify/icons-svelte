<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yngda3bvc"/><path class="x1_r36phd"/><path class="rrzohjbez"/><path class="gstzuxb9r"/><path class="wggowmhtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rowing-machine-outline-bold" {...props}></Icon>
<style>
:global(.gstzuxb9r) {
  d: path("M5 7v4");
}

:global(.rrzohjbez) {
  d: path("M12 12v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wggowmhtc) {
  d: path("M5 9h4");
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.yngda3bvc) {
  d: path("M3 15h18");
}

</style>

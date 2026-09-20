<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g_k4bub3x"/><path class="guw4_4ovg"/><path class="r9il7jbjw"/><path class="gzes1rhcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tip-jar-outline-regular" {...props}></Icon>
<style>
:global(.g_k4bub3x) {
  d: path("M6 9h12v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3Z");
}

:global(.guw4_4ovg) {
  d: path("M8 9V4h8v5");
}

:global(.gzes1rhcl) {
  d: path("M12 13.5v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r9il7jbjw) {
  d: path("M9 15.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u__n76blo"/><path class="m6cyaabzz"/><path class="t0l5cz7rn"/><path class="zyz2vdbji"/><path class="zrqurcb-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:schedule-report-outline-regular" {...props}></Icon>
<style>
:global(.m6cyaabzz) {
  d: path("M8 3v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t0l5cz7rn) {
  d: path("M16 3v5");
}

:global(.u__n76blo) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.zrqurcb-a) {
  d: path("M5 15h8");
}

:global(.zyz2vdbji) {
  d: path("M5 11h12");
}

</style>

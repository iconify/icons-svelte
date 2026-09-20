<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j534ltbcb"/><path class="m1mjigbsi"/><path class="d1zyr9bfc"/><path class="k7u-15-va"/><path class="ghf6zpb7j"/><path class="c4khiwgvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tracking-number-outline-regular" {...props}></Icon>
<style>
:global(.c4khiwgvb) {
  d: path("M8 15h8");
}

:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.ghf6zpb7j) {
  d: path("M14 12v6");
}

:global(.j534ltbcb) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.k7u-15-va) {
  d: path("M10 12v6");
}

:global(.m1mjigbsi) {
  d: path("M4 8h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pek-tswzf"/><path class="dak2_9b1i"/><path class="hxoe7gx5p"/><path class="fyt8fyb5h"/><path class="x-egzxztr"/><path class="eg0ecwbhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:score-distribution-outline-regular" {...props}></Icon>
<style>
:global(.dak2_9b1i) {
  d: path("M8 9v8");
}

:global(.eg0ecwbhj) {
  d: path("M3 19.5h18");
}

:global(.fyt8fyb5h) {
  d: path("M16 9v8");
}

:global(.hxoe7gx5p) {
  d: path("M12 5v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pek-tswzf) {
  d: path("M4 13v4");
}

:global(.x-egzxztr) {
  d: path("M20 13v4");
}

</style>

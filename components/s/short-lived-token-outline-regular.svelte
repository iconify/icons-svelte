<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b2a9_acks"/><path class="ziznm1ama"/><path class="ny9m1pboy"/><path class="yaetm9cyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:short-lived-token-outline-regular" {...props}></Icon>
<style>
:global(.b2a9_acks) {
  d: path("M2 12a3 3 0 0 1 3 -3h6a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ny9m1pboy) {
  d: path("M18 9.5V12");
}

:global(.yaetm9cyz) {
  d: path("M18 12h2.5");
}

:global(.ziznm1ama) {
  d: path("M14 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>

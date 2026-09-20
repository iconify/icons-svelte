<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vezho9b5g"/><path class="ul-6megvv"/><path class="hb39b-bug"/><path class="lqktbo2ou"/><path class="ejc7sbawl"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:volume-anomaly-outline-regular" {...props}></Icon>
<style>
:global(.ejc7sbawl) {
  d: path("M20 15v4");
}

:global(.hb39b-bug) {
  d: path("M12 3v16");
}

:global(.lqktbo2ou) {
  d: path("M16 12v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ul-6megvv) {
  d: path("M8 11v8");
}

:global(.vezho9b5g) {
  d: path("M4 14v5");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>

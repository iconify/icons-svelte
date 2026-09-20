<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><path class="jkuojibnm"/><path class="h7bcztycq"/><path class="bhl_zu55p"/><path class="p9jmvgbqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spacer-outline-regular" {...props}></Icon>
<style>
:global(.bhl_zu55p) {
  d: path("M9.5 10.5 12 8l2.5 2.5");
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p9jmvgbqq) {
  d: path("M9.5 13.5 12 16l2.5 -2.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="t0-mwc0xy"/><path class="o3x_gzblq"/><path class="qik8460ao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vacuum-db-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.o3x_gzblq) {
  d: path("m8 13 4 4 4 -4");
}

:global(.qik8460ao) {
  d: path("M5 21h14");
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

</style>

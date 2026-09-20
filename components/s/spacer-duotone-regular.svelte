<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajs51ib"/><path class="pga6n1bci"/><path class="ewy1wiqaa"/><path class="ogpebzpji"/><path class="f_lolk89u"/><path class="mg7aqnbsf"/><path class="jkuojibnm"/><path class="h7bcztycq"/><path class="bhl_zu55p"/><path class="p9jmvgbqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spacer-duotone-regular" {...props}></Icon>
<style>
:global(.bhl_zu55p) {
  d: path("M9.5 10.5 12 8l2.5 2.5");
}

:global(.ewy1wiqaa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f_lolk89u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 13.5 12 16l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.ogpebzpji) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 10.5 12 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p9jmvgbqq) {
  d: path("M9.5 13.5 12 16l2.5 -2.5");
}

:global(.pga6n1bci) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s1ajs51ib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

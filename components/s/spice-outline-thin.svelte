<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ste6xgm2r"/><path class="f_ocwm2xq"/><path class="fkf_gcbra"/><path class="ugvz7ebru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spice-outline-thin" {...props}></Icon>
<style>
:global(.f_ocwm2xq) {
  d: path("M10 10V6h4v4");
}

:global(.fkf_gcbra) {
  d: path("M10 15h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ste6xgm2r) {
  d: path("M7 10v11h10V10Z");
}

:global(.ugvz7ebru) {
  d: path("M10 18h4");
}

</style>

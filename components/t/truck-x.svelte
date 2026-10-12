<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmlr-rd6a"/><circle class="w0wkfousa"/><circle class="c404t1u9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:truck-x" {...props}></Icon>
<style>
:global(.c404t1u9v) {
  cx: 17px;
  cy: 19.25px;
  r: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pmlr-rd6a) {
  d: path("M2.75 6.25a1.5 1.5 0 0 1 1.5-1.5h9a1.5 1.5 0 0 1 1.5 1.5v2h3.15a1.5 1.5 0 0 1 1.25.67L21 11.7a1 1 0 0 1 .25.66V14a1 1 0 0 1-1 1h-16a1.5 1.5 0 0 1-1.5-1.5Zm12 2V15");
}

:global(.w0wkfousa) {
  cx: 7.25px;
  cy: 19.25px;
  r: 1.5px;
}

</style>

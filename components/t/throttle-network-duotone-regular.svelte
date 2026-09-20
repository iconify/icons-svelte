<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hi-cbzcqh"/><path class="ah5k37b7w"/><path class="asd1gsbjs"/><path class="b9eq8li1d"/><path class="nwdk136nn"/><path class="f1vpicczb"/><path class="o0-3vqblf"/><path class="jcxg2bbvb"/><path class="e-p0c9bfw"/><path class="jlfl_ccwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:throttle-network-duotone-regular" {...props}></Icon>
<style>
:global(.ah5k37b7w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.asd1gsbjs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b9eq8li1d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 3 6 6v6l-6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e-p0c9bfw) {
  d: path("m8 3 6 6v6l-6 6");
}

:global(.f1vpicczb) {
  d: path("M2 4h8");
}

:global(.hi-cbzcqh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 4h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.jlfl_ccwj) {
  d: path("M14 12h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nwdk136nn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o0-3vqblf) {
  d: path("M2 8h8");
}

</style>

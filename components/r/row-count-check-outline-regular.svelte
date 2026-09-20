<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsy-y08mq"/><path class="sixdm4bhp"/><path class="sgz4g8k3l"/><path class="ievtq1brs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:row-count-check-outline-regular" {...props}></Icon>
<style>
:global(.ievtq1brs) {
  d: path("M14.5 17.5 17 20l4.5 -4.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rsy-y08mq) {
  d: path("M3 4h14");
}

:global(.sgz4g8k3l) {
  d: path("M3 14h14");
}

:global(.sixdm4bhp) {
  d: path("M3 9h14");
}

</style>

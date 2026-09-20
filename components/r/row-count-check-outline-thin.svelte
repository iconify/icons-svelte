<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsy-y08mq"/><path class="sixdm4bhp"/><path class="sgz4g8k3l"/><path class="ievtq1brs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:row-count-check-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ievtq1brs) {
  d: path("M14.5 17.5 17 20l4.5 -4.5");
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

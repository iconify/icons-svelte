<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrnt518ve"/><path class="ymxftgbgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:snowboard-binding" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrnt518ve) {
  d: path("M5.25 7Q12 8.5 18.75 7a2.75 2.75 0 0 1 2.75 2.75v4.5A2.75 2.75 0 0 1 18.75 17Q12 15.5 5.25 17a2.75 2.75 0 0 1-2.75-2.75v-4.5A2.75 2.75 0 0 1 5.25 7");
}

:global(.ymxftgbgf) {
  d: path("M8.25 5zA1.75 1.75 0 0 1 10 6.75v10.5A1.75 1.75 0 0 1 8.25 19a1.75 1.75 0 0 1-1.75-1.75V6.75A1.75 1.75 0 0 1 8.25 5m7.5 0za1.75 1.75 0 0 1 1.75 1.75v10.5A1.75 1.75 0 0 1 15.75 19A1.75 1.75 0 0 1 14 17.25V6.75A1.75 1.75 0 0 1 15.75 5");
}

</style>

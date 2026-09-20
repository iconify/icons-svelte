<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8jtagpjt"/><path class="leo1-zbey"/><path class="l_u_8t5pe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rsvp-outline-thin" {...props}></Icon>
<style>
:global(.c8jtagpjt) {
  d: path("M7 9v10h14V9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l_u_8t5pe) {
  d: path("m6 11 -3 3 3 3");
}

:global(.leo1-zbey) {
  d: path("m7 9 7 7 7 -7");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nyh2wr5qz"/><path class="tyqpq712i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ski-wax" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nyh2wr5qz) {
  d: path("M5 19.5v-9.414a1.5 1.5 0 0 1 .398-1.017l5.157-5.586A1.5 1.5 0 0 1 11.657 3H17.5A1.5 1.5 0 0 1 19 4.5v12.138a1.5 1.5 0 0 1-.744 1.296l-4.906 2.862a1.5 1.5 0 0 1-.756.204H6.5A1.5 1.5 0 0 1 5 19.5");
}

:global(.tyqpq712i) {
  d: path("M5 9.5h8V21m0-11.5L19 3");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqp7iikvz"/><path class="qq8av8fom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:watering-globe" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qq8av8fom) {
  d: path("M12 5s-1.75 2.25-1.75 3.5a1.75 1.75 0 0 0 3.5 0C13.75 7.25 12 5 12 5");
}

:global(.wqp7iikvz) {
  d: path("M6.5 7.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0M12 13v3m-3.808 0h7.616a1.75 1.75 0 0 1 1.706 2.138l-.454 2a1.75 1.75 0 0 1-1.707 1.362H8.647a1.75 1.75 0 0 1-1.707-1.362l-.454-2A1.75 1.75 0 0 1 8.192 16");
}

</style>

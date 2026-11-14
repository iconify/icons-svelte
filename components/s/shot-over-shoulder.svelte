<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="ievc98bfa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shot-over-shoulder" {...props}></Icon>
<style>
:global(.hneliqdkn) {
  d: path("M2.5 4h19v16h-19Z");
}

:global(.ievc98bfa) {
  d: path("M2.5 9a4.5 4.5 0 0 1 0 9m9.25-8.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM10 20c0-3 2-5 4.5-5s4.5 2 4.5 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

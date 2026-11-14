<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hcauwkbvm"/><path class="ighr8abuq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ski-tracks" {...props}></Icon>
<style>
:global(.hcauwkbvm) {
  d: path("M6 21.5c0-5.5 6.5-7 6.5-12.5c0-3-1.5-5-3.5-6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ighr8abuq) {
  d: path("M10 21.5c0-5.5 6.5-7 6.5-12.5c0-3-1.5-5-3.5-6.5");
}

</style>

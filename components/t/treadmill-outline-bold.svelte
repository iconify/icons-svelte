<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h67al40ex"/><path class="wre--v3de"/><path class="ned58dbax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:treadmill-outline-bold" {...props}></Icon>
<style>
:global(.h67al40ex) {
  d: path("M2 19h13v-4H2Z");
}

:global(.ned58dbax) {
  d: path("M16 8h6V4h-6Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wre--v3de) {
  d: path("M15 17h4V8");
}

</style>

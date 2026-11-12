<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pp0x4sctl"/><path class="yv74hxect"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-box-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pp0x4sctl) {
  stroke-opacity: 0.4;
  d: path("m7.5 9.222l4.5 2.222l4.5-2.222M12 11.444V17");
}

:global(.yv74hxect) {
  d: path("M3 3h18v18H3Zm9 4l4.5 2.222v5.556L12 17l-4.5-2.222V9.222z");
}

</style>

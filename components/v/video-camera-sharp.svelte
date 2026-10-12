<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="x1c2bobhh"/><path class="obcntljhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:video-camera-sharp" {...props}></Icon>
<style>
:global(.obcntljhj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 12.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.x1c2bobhh) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 8.75v-4h9v4m-12 0h14v10.5h-14zm14 2h4.5v6.5h-4.5z");
}

</style>

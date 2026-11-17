<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0u3ty-jh"/><path class="h44n_-b6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-flame-duocolor-sharp" {...props}></Icon>
<style>
:global(.h44n_-b6n) {
  d: path("M8.833 3L3 10.333h3.5V15l5.833-7.333h-3.5zM17 9c.333 1.667 1.333 3 2.667 4c1 1 1.333 2.333 1.333 4a4 4 0 1 1-8 0c0-1 .333-1.667.667-2");
}

:global(.n0u3ty-jh) {
  stroke-opacity: 0.4;
  d: path("M13.667 15a1.333 1.333 0 1 0 2.666 0c0-1-.333-1.333-.666-2C15 11.667 15.333 10.333 17 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

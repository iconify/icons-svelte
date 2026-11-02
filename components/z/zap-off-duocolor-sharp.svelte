<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sr6trvpei"/><path class="wu8u2fhnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sr6trvpei) {
  stroke-opacity: 0.4;
  d: path("m2 5l17 17");
}

:global(.wu8u2fhnb) {
  d: path("m17 14l3-3h-6V3l-4 4m-3 3l-3 3h6v8l4-4");
}

</style>

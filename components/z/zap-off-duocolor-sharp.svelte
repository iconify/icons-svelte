<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sr6trvpei"/><path class="huu624itn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.huu624itn) {
  d: path("M16.342 13.342L19 10h-5.25V3l-3.434 4.316m-2.658 3.342L5 14h5.25v7l3.434-4.316");
}

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

</style>

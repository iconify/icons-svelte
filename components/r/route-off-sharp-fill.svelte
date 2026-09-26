<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fubjnnb6d"/><path class="vqtuzsypa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:route-off-sharp-fill" {...props}></Icon>
<style>
:global(.fubjnnb6d) {
  fill: currentColor;
  d: path("M10 18C10 20.0711 8.0711 22 6 22C3.9289 22 2 20.0711 2 18C2 15.9289 3.9289 14 6 14C8.0711 14 10 15.9289 10 18Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vqtuzsypa) {
  d: path("M8 18L18 18M18 13.3431L18 3M14.7071 6.2929L18 3L21.2929 6.2929M1.7071 1.7071L22.2929 22.2929");
}

</style>

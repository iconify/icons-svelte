<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s446_nmsp"/><path class="jcsm0pv6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:timer-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.jcsm0pv6v) {
  d: path("M12 6C16.4183 6 20 9.5817 20 14C20 18.4183 16.4183 22 12 22C7.5817 22 4 18.4183 4 14C4 9.5817 7.5817 6 12 6ZM8 2L16 2M12 2L12 6M12 15L12 9M17.6569 8.3431L19.2929 6.7071");
}

:global(.s446_nmsp) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 5C16.9706 5 21 9.0294 21 14C21 18.9706 16.9706 23 12 23C7.0294 23 3 18.9706 3 14C3 9.0294 7.0294 5 12 5Z");
  stroke: none;
}

</style>

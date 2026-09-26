<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n3rr8texm"/><path class="xmeb_n1nn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.n3rr8texm) {
  fill: currentColor;
  d: path("M20 11C20 15.8326 15.8326 20 11 20C6.1674 20 2 15.8326 2 11C2 6.1674 6.1674 2 11 2C15.8326 2 20 6.1674 20 11Z");
  stroke: none;
}

:global(.xmeb_n1nn) {
  d: path("M16.2929 16.2929L21.2929 21.2929");
}

</style>

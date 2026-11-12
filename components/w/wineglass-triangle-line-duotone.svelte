<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vb8us5ilq"/><path class="doqa-cbwv"/><path class="xeoh7lbiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wineglass-triangle-line-duotone" {...props}></Icon>
<style>
:global(.doqa-cbwv) {
  d: path("M12 14.5713V20.9999");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vb8us5ilq) {
  d: path("M16.2439 21H7.7561M4.70095 3H19.2991C20.7999 3 21.5624 4.79409 20.5162 5.86382L12.7149 13.8404C12.3227 14.2415 11.6773 14.2415 11.2851 13.8404L3.48381 5.86382C2.43759 4.79409 3.20008 3 4.70095 3Z");
}

:global(.xeoh7lbiu) {
  d: path("M7.47314 9.75H16.5268");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>

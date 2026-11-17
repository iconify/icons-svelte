<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="awpzzfbhl"/><path class="rf5dn__pe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scale-duotone" {...props}></Icon>
<style>
:global(.awpzzfbhl) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6 6l3 7a3.25 3.25 0 0 1-6 0Zm12 0l3 7a3.25 3.25 0 0 1-6 0Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.rf5dn__pe) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3v18m-4 0h8M6 6h12M6 6l3 7a3.25 3.25 0 0 1-6 0Zm12 0l3 7a3.25 3.25 0 0 1-6 0Z");
}

</style>

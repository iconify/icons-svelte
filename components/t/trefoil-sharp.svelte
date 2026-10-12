<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jvq4z_pej"/><path class="afk3glbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trefoil-sharp" {...props}></Icon>
<style>
:global(.afk3glbhf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.75h.01");
}

:global(.jvq4z_pej) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.1 10.5a4.5 4.5 0 1 1 7.8 0a4.5 4.5 0 1 1-3.9 6.75a4.5 4.5 0 1 1-3.9-6.75Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

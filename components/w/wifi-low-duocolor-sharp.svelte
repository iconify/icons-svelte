<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z37wupstu"/><path class="eyhvntpqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wifi-low-duocolor-sharp" {...props}></Icon>
<style>
:global(.eyhvntpqg) {
  d: path("M12 19h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z37wupstu) {
  stroke-opacity: 0.4;
  d: path("M9 16c1.427-2.14 4.573-2.14 6 0");
}

</style>

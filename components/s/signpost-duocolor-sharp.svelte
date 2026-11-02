<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e3xlw3esn"/><path class="bndddt2vm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:signpost-duocolor-sharp" {...props}></Icon>
<style>
:global(.bndddt2vm) {
  d: path("M10 6h7l3 3l-3 3H4V6z");
}

:global(.e3xlw3esn) {
  stroke-opacity: 0.4;
  d: path("M12 3v3m0 6v9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h4f42dbzz"/><path class="l2emg7y9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-minus-duocolor-sharp" {...props}></Icon>
<style>
:global(.h4f42dbzz) {
  stroke-opacity: 0.4;
  d: path("M15 12h6");
}

:global(.l2emg7y9m) {
  d: path("M11 4v16l-4-4H3V8h4z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

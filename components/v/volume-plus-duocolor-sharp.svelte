<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="suobsmife"/><path class="l2emg7y9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-plus-duocolor-sharp" {...props}></Icon>
<style>
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

:global(.suobsmife) {
  stroke-opacity: 0.4;
  d: path("M15 12h6m-3-3v6");
}

</style>

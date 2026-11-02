<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nuvbu6bqy"/><path class="t8q_ld_2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:telescope-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nuvbu6bqy) {
  stroke-opacity: 0.4;
  d: path("M12 11L7 21m5-10l5 10");
}

:global(.t8q_ld_2l) {
  d: path("m4 10l14-7l2 4l-14 7zm10-5l2 4");
}

</style>

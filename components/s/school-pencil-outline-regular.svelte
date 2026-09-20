<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rxedw8b6o"/><path class="iq9in6bpg"/><path class="wsj78vmsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-pencil-outline-regular" {...props}></Icon>
<style>
:global(.iq9in6bpg) {
  d: path("m7 16 -3 3h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rxedw8b6o) {
  d: path("m7 16 9 -9 3 3 -9 9Z");
}

:global(.wsj78vmsl) {
  d: path("m14 9 3 3");
}

</style>

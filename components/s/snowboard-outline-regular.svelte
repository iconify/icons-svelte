<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nbhxjjbfa"/><path class="ndkxcpb5b"/><path class="qaqzxor9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:snowboard-outline-regular" {...props}></Icon>
<style>
:global(.nbhxjjbfa) {
  d: path("M6 21C3 18 3 6 6 3c3 3 3 15 0 18");
}

:global(.ndkxcpb5b) {
  d: path("M12 16h5v3h-5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qaqzxor9c) {
  d: path("M12 6h5v3h-5Z");
}

</style>

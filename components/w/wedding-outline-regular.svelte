<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x_1pk7qez"/><path class="nebfuhbln"/><path class="b8yphbcwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wedding-outline-regular" {...props}></Icon>
<style>
:global(.b8yphbcwk) {
  d: path("m10 7 2 -2 2 2 -2 2Z");
}

:global(.nebfuhbln) {
  d: path("M12 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x_1pk7qez) {
  d: path("M4 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>

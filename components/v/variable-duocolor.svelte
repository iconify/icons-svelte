<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tqffmp7ti"/><path class="aa5qvwn9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:variable-duocolor" {...props}></Icon>
<style>
:global(.aa5qvwn9h) {
  d: path("M7 5C3 9 3 15 7 19M17 5c4 4 4 10 0 14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tqffmp7ti) {
  stroke-opacity: 0.4;
  d: path("m9 9l6 6m0-6l-6 6");
}

</style>

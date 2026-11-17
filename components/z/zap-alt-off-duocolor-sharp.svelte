<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sr6trvpei"/><path class="st0qwlgbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-alt-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sr6trvpei) {
  stroke-opacity: 0.4;
  d: path("m2 5l17 17");
}

:global(.st0qwlgbh) {
  d: path("M8.77 5.77L10 3h7l-4 7h5l-2 2m-3.5 3.5L7 21l2-9H6l.923-2.077");
}

</style>

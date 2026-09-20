<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tuxrk23ou"/><path class="i5qiurazi"/><path class="vc425bcyv"/><path class="nca7pq6lm"/><path class="qcx0_7byx"/><path class="dwj8i8b7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:social-event-duotone-regular" {...props}></Icon>
<style>
:global(.dwj8i8b7i) {
  d: path("M6 10c1 2 3 2 4 0 1 2 3 2 4 0 1 2 3 2 4 0");
}

:global(.i5qiurazi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10v10h12V10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nca7pq6lm) {
  d: path("m4 10 8 -8 8 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qcx0_7byx) {
  d: path("M6 10v10h12V10");
}

:global(.tuxrk23ou) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 10 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vc425bcyv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10c1 2 3 2 4 0 1 2 3 2 4 0 1 2 3 2 4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

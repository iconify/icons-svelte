<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fxaerfbaz"/><path class="naf5gjb6k"/><path class="e0fatccfd"/><path class="cjddu477a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:welcome-party-outline-regular" {...props}></Icon>
<style>
:global(.cjddu477a) {
  d: path("m20 10 -2 2 2 2");
}

:global(.e0fatccfd) {
  d: path("M18 12h4");
}

:global(.fxaerfbaz) {
  d: path("M6 20V4h10v16");
}

:global(.naf5gjb6k) {
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

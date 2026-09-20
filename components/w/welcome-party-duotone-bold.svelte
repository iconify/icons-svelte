<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y8h-esezl"/><path class="ucn3qlbgp"/><path class="jtcv4c9tp"/><path class="njc0tpbau"/><path class="fxaerfbaz"/><path class="naf5gjb6k"/><path class="e0fatccfd"/><path class="cjddu477a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:welcome-party-duotone-bold" {...props}></Icon>
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

:global(.jtcv4c9tp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.naf5gjb6k) {
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.njc0tpbau) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 10 -2 2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ucn3qlbgp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 20V4h10v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y8h-esezl) {
  fill: currentColor;
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

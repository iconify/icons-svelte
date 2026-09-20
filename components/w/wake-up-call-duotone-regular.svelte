<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pw3t53bda"/><path class="nqda50bqs"/><path class="fxnzc9b-v"/><path class="bh28pgoco"/><path class="fcb5akbfg"/><path class="txeai18yr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wake-up-call-duotone-regular" {...props}></Icon>
<style>
:global(.bh28pgoco) {
  d: path("M12 13h4");
}

:global(.fcb5akbfg) {
  d: path("m5 5 3 3");
}

:global(.fxnzc9b-v) {
  d: path("M12 9v4");
}

:global(.nqda50bqs) {
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pw3t53bda) {
  fill: currentColor;
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.txeai18yr) {
  d: path("m19 5 -3 3");
}

</style>

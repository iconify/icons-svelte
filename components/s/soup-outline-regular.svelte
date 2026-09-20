<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xi253xtcz"/><path class="comy-yirf"/><path class="akhrngbmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:soup-outline-regular" {...props}></Icon>
<style>
:global(.akhrngbmf) {
  d: path("M15 10c2 -2 0 -4 2 -6");
}

:global(.comy-yirf) {
  d: path("M9 10c2 -2 0 -4 2 -6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xi253xtcz) {
  d: path("M4 12h16c0 5 -4 9 -8 9s-8 -4 -8 -9");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g01zyvbwi"/><path class="v5srdkbdr"/><path class="ysaawnbjv"/><path class="wriot4b8j"/><path class="cf8eb9bym"/><path class="j3rg9kqcf"/><path class="lk3noub5u"/><path class="azsxw4yri"/><path class="kg1t7rbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sun-outline-regular" {...props}></Icon>
<style>
:global(.azsxw4yri) {
  d: path("m5 19 2.5 -2.5");
}

:global(.cf8eb9bym) {
  d: path("M18.5 12H22");
}

:global(.g01zyvbwi) {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.j3rg9kqcf) {
  d: path("m5 5 2.5 2.5");
}

:global(.kg1t7rbnq) {
  d: path("m19 19 -2.5 -2.5");
}

:global(.lk3noub5u) {
  d: path("m19 5 -2.5 2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v5srdkbdr) {
  d: path("M12 2v3.5");
}

:global(.wriot4b8j) {
  d: path("M2 12h3.5");
}

:global(.ysaawnbjv) {
  d: path("M12 18.5V22");
}

</style>

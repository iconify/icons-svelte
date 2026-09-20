<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b4gdm4amb"/><path class="v-ecc6-9c"/><path class="kp6e_l5bx"/><path class="kn820ue-q"/><path class="t3rzvj9ww"/><path class="sdu6a9xcp"/><path class="va9i39bae"/><path class="y07a50u1t"/><path class="pbz4y6llk"/><path class="c3wl0l-ou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:test-tube-duotone-bold" {...props}></Icon>
<style>
:global(.b4gdm4amb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 3v12l3 3 3 -3V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c3wl0l-ou) {
  d: path("M19 13v6");
}

:global(.kn820ue-q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kp6e_l5bx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pbz4y6llk) {
  d: path("M5 13v6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sdu6a9xcp) {
  d: path("M9 3v12l3 3 3 -3V3");
}

:global(.t3rzvj9ww) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v-ecc6-9c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.va9i39bae) {
  d: path("M7 3h10");
}

:global(.y07a50u1t) {
  d: path("M5 13h14");
}

</style>

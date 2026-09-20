<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uau0kschl"/><path class="ja7s-m1mr"/><path class="ti2-e6mha"/><path class="ex7acbbzc"/><path class="esx8xg2rn"/><path class="yngda3bvc"/><path class="x1_r36phd"/><path class="rrzohjbez"/><path class="gstzuxb9r"/><path class="wggowmhtc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rowing-machine-duotone-thin" {...props}></Icon>
<style>
:global(.esx8xg2rn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 9h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ex7acbbzc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gstzuxb9r) {
  d: path("M5 7v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja7s-m1mr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rrzohjbez) {
  d: path("M12 12v3");
}

:global(.ti2-e6mha) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uau0kschl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wggowmhtc) {
  d: path("M5 9h4");
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.yngda3bvc) {
  d: path("M3 15h18");
}

</style>

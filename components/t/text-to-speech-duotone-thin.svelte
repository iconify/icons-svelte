<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eo10586qe"/><path class="lv3yajb7o"/><path class="talm7881m"/><path class="agubc-b0y"/><path class="bonttq6md"/><path class="u5fp3_7hb"/><path class="six8rqb9w"/><path class="nu8u0dbfs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-to-speech-duotone-thin" {...props}></Icon>
<style>
:global(.agubc-b0y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 6.8a6 6 0 0 1 0 10.4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bonttq6md) {
  d: path("M2 9h8");
}

:global(.eo10586qe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lv3yajb7o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nu8u0dbfs) {
  d: path("M17 6.8a6 6 0 0 1 0 10.4");
}

:global(.six8rqb9w) {
  d: path("M15.5 9.4a3 3 0 0 1 0 5.2");
}

:global(.talm7881m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 9.4a3 3 0 0 1 0 5.2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u5fp3_7hb) {
  d: path("M2 13h6");
}

</style>

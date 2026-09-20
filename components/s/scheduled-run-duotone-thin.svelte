<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y9e33ibiz"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="gud1vabey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scheduled-run-duotone-thin" {...props}></Icon>
<style>
:global(.gud1vabey) {
  d: path("m10 10 4 4 -4 4Z");
}

:global(.hk697hhuu) {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jms1xqp8l) {
  d: path("M9 3h6");
}

:global(.y9e33ibiz) {
  fill: currentColor;
  d: path("m10 10 4 4 -4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>

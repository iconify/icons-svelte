<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jlxwz7w4c"/><path class="ft030md1w"/><path class="ammvvefwf"/><path class="mf7n6gbnt"/><path class="skbifdbcx"/><path class="mk37pkb8m"/><path class="xupj3fbjb"/><path class="k5yx_gble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:subscribe-agent-duotone-thin" {...props}></Icon>
<style>
:global(.ammvvefwf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 15a3 3 0 0 1 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ft030md1w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jlxwz7w4c) {
  fill: currentColor;
  d: path("M12 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k5yx_gble) {
  d: path("M12 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mf7n6gbnt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 12a6 6 0 0 1 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mk37pkb8m) {
  d: path("M13 15a3 3 0 0 1 3 3");
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

:global(.xupj3fbjb) {
  d: path("M13 12a6 6 0 0 1 6 6");
}

</style>

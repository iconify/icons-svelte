<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="skbifdbcx"/><path class="mk37pkb8m"/><path class="xupj3fbjb"/><path class="k5yx_gble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:subscribe-agent-outline-regular" {...props}></Icon>
<style>
:global(.k5yx_gble) {
  d: path("M12 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mk37pkb8m) {
  d: path("M13 15a3 3 0 0 1 3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

:global(.xupj3fbjb) {
  d: path("M13 12a6 6 0 0 1 6 6");
}

</style>

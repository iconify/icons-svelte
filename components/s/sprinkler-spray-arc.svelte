<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9-adccac"/><path class="sgls5rb0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sprinkler-spray-arc" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sgls5rb0c) {
  d: path("M12 12.5c2-9 8-9 9.5 2.5M12 12.5c-2-9-8-9-9.5 2.5");
}

:global(.v9-adccac) {
  d: path("M12 21.5v-7m-1-2h2a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1a1 1 0 0 1 1-1m-6 9h14");
}

</style>

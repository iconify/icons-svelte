<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jnay8pbpe"/><path class="e7vch8rsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:vo2-max-duotone-thin" {...props}></Icon>
<style>
:global(.e7vch8rsw) {
  d: path("M12 3v5m0 0c-4 0 -7 3 -7 7 0 3 1 5 4 5 2 0 3 -1 3 -4 0 3 1 4 3 4 3 0 4 -2 4 -5 0 -4 -3 -7 -7 -7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jnay8pbpe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v5m0 0c-4 0 -7 3 -7 7 0 3 1 5 4 5 2 0 3 -1 3 -4 0 3 1 4 3 4 3 0 4 -2 4 -5 0 -4 -3 -7 -7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ab48ccc0f"/><path class="u3mqizjgw"/><path class="k311anbdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:toy-brick-outline-thin" {...props}></Icon>
<style>
:global(.ab48ccc0f) {
  d: path("M4 9v10h16V9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k311anbdb) {
  d: path("M14 9V6h3v3");
}

:global(.u3mqizjgw) {
  d: path("M7 9V6h3v3");
}

</style>

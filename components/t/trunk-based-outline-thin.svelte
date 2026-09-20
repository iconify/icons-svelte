<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h2-2dgnfu"/><path class="srofgib5x"/><path class="m7gli2e_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trunk-based-outline-thin" {...props}></Icon>
<style>
:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m7gli2e_k) {
  d: path("M16.5 12.5 12 17");
}

:global(.srofgib5x) {
  d: path("M7.5 6.5 12 11");
}

</style>

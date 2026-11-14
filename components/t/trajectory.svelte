<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vt4qe7bak"/><path class="lj14osbeo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:trajectory" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lj14osbeo) {
  d: path("M16 12.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M2.5 20h19");
}

:global(.vt4qe7bak) {
  d: path("M4 20C6 4 14 2.5 17.5 10");
}

</style>

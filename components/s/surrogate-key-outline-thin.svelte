<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lo7kp72nh"/><path class="mjuhvrbig"/><path class="zg6stybep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:surrogate-key-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lo7kp72nh) {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.mjuhvrbig) {
  d: path("M9 8h9v9");
}

:global(.zg6stybep) {
  d: path("M16 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

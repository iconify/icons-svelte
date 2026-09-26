<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lxbz0e66a"/><path class="lz1dchbpw"/><path class="t7jitqb_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-columns-add-before-duotone" {...props}></Icon>
<style>
:global(.lxbz0e66a) {
  stroke-opacity: 0.4;
  d: path("M4.1716 19C4.5954 20.1986 5.7287 21 7 21L13 21M13 3L7 3C5.7287 3 4.5954 3.8014 4.1716 5");
}

:global(.lz1dchbpw) {
  fill: currentColor;
  d: path("M12 22L12 2L19 2C21.2091 2 23 3.7909 23 6L23 18C23 20.2091 21.2091 22 19 22L12 22Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t7jitqb_d) {
  d: path("M5 9L5 15M2 12L8 12");
}

</style>

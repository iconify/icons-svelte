<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l3tmkcfwm"/><circle class="odfkfz5qm"/><path class="ke_4cxbzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:visibility" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ke_4cxbzd) {
  d: path("M2.75 20.5h7.5m3.5 0h7.5");
}

:global(.l3tmkcfwm) {
  d: path("M2.75 10.5c2.5-4 5.75-6 9.25-6s6.75 2 9.25 6c-2.5 4-5.75 6-9.25 6s-6.75-2-9.25-6");
}

:global(.odfkfz5qm) {
  cx: 12px;
  cy: 10.5px;
  r: 2.5px;
}

</style>

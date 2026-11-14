<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm7p6vh3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stair-handrail" {...props}></Icon>
<style>
:global(.dm7p6vh3d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5H8V15h5.5V9.5h8M4 15L16.5 2.5M5.25 13.75v6.75m10.5-17.25V9.5");
}

</style>

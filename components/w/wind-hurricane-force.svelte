<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urwm_e-me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wind-hurricane-force" {...props}></Icon>
<style>
:global(.urwm_e-me) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5h14a3 3 0 1 0-3-3m-11 6.75h16a3 3 0 1 1-3 3m-13 1H11a2.5 2.5 0 1 1-2.5 2.5");
}

</style>

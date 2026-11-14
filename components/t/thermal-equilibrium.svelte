<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s08bt5oay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thermal-equilibrium" {...props}></Icon>
<style>
:global(.s08bt5oay) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5v15a2 2 0 0 0 2 2h.5a2 2 0 0 0 2-2v-15m9 0v15a2 2 0 0 0 2 2h.5a2 2 0 0 0 2-2v-15M3 12h4.5m9 0H21m-10.75-1.5h3.5m-3.5 3h3.5");
}

</style>

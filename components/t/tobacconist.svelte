<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqjxp1cxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tobacconist" {...props}></Icon>
<style>
:global(.tqjxp1cxx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 10.5h8v5a4 4 0 0 1-8 0ZM3 13l10 2.5m4-7C15.5 7 18.5 6 17 4");
}

</style>

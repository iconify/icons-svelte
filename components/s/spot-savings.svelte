<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olmzg42vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:spot-savings" {...props}></Icon>
<style>
:global(.olmzg42vc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 12.5l10-10m-11.5 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0m9 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2.5 5v6m-3-3l3 3l3-3");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl7zabbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sale-megaphone" {...props}></Icon>
<style>
:global(.jl7zabbhg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.5h4l9-5v15l-9-5H4Zm4 5L9.5 20M20 9.5v5");
}

</style>

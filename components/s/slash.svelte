<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se83abbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:slash" {...props}></Icon>
<style>
:global(.se83abbxw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16 3.5l-8 17");
}

</style>

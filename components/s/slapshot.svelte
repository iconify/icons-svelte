<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4xjn2vde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:slapshot" {...props}></Icon>
<style>
:global(.u4xjn2vde) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.5 2.5l-7 15h-5m9.5.5a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0Z");
}

</style>

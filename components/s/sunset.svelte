<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spvk_ghjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sunset" {...props}></Icon>
<style>
:global(.spvk_ghjr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 19.5a5 5 0 0 1 10 0m-14.5 0h19M12 4v7.5M9.5 9l2.5 2.5L14.5 9m-8 5L5 12.5M17.5 14l1.5-1.5");
}

</style>

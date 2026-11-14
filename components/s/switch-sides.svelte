<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udnbbdbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:switch-sides" {...props}></Icon>
<style>
:global(.udnbbdbni) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v18M4 8h16m-3.5-3.5L20 8l-3.5 3.5M20 16H4m3.5-3.5L4 16l3.5 3.5");
}

</style>

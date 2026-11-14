<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stxf65jfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:squat-lift" {...props}></Icon>
<style>
:global(.stxf65jfc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5.5 9.25h13m-6 0L9 15l5.5 1.75l-2 4.75h3.25M3 5.25h2.5v8H3Zm15.5 0H21v8h-2.5Z");
}

</style>

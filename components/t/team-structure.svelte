<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc84tmbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:team-structure" {...props}></Icon>
<style>
:global(.zc84tmbnc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.75 6c0-2 1.25-3 2.75-3s2.75 1 2.75 3ZM3 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.75 6c0-2 1.25-3 2.75-3s2.75 1 2.75 3ZM17 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.75 6c0-2 1.25-3 2.75-3s2.75 1 2.75 3Zm-6.5-8.5L7 12.75m7.25-1.25L17 12.75M9.75 18.5h4.5");
}

</style>

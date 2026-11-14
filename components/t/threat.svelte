<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huacqwbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:threat" {...props}></Icon>
<style>
:global(.huacqwbsg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5a5.5 5.5 0 0 1 11 0c0 1.75-.75 3-2 3.75V15h-7v-1.75c-1.25-.75-2-2-2-3.75Zm3.25 0h.01m4.49 0h.01M4.5 17l15 4m0-4l-15 4");
}

</style>

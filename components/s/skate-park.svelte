<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjsadsjsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skate-park" {...props}></Icon>
<style>
:global(.sjsadsjsl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.5 19h-19v-9h7a9 9 0 0 0 9 9M3 6.75l.75.75h4.5L9 6.75M4.75 9h.01m2.49 0h.01");
}

</style>

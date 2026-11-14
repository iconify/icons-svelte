<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc9ub2nfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:snow-brush" {...props}></Icon>
<style>
:global(.bc9ub2nfj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v9m-4.75 0h9.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 16.75 15h-9.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75M7.5 15v5.5m3-5.5v5.5m3-5.5v5.5m3-5.5v5.5");
}

</style>

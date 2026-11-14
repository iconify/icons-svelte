<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_f8ibc-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:squircle" {...props}></Icon>
<style>
:global(.u_f8ibc-p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c8.5 0 9.5 1 9.5 9.5s-1 9.5-9.5 9.5s-9.5-1-9.5-9.5s1-9.5 9.5-9.5");
}

</style>

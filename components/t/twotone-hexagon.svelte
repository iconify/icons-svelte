<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rca52mb-x"/><path class="g0r1g8t_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-hexagon" {...props}></Icon>
<style>
:global(.g0r1g8t_h) {
  fill: currentColor;
  d: path("M17.2 3H6.8l-5.2 9l5.2 9h10.4l5.2-9zm-1.15 16h-8.1l-4.04-7l4.04-7h8.09l4.04 7z");
}

:global(.rca52mb-x) {
  fill: currentColor;
  d: path("M16.05 19h-8.1l-4.04-7l4.04-7h8.1l4.04 7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

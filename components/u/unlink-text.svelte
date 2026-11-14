<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbjcb-l3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:unlink-text" {...props}></Icon>
<style>
:global(.zbjcb-l3z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.672 16.793l2.121-2.121a2.5 2.5 0 0 1 3.535 0a2.5 2.5 0 0 1 0 3.535l-2.121 2.121a2.5 2.5 0 0 1-3.535 0a2.5 2.5 0 0 1 0-3.535m11-11l2.121-2.121a2.5 2.5 0 0 1 3.535 0a2.5 2.5 0 0 1 0 3.535l-2.121 2.121a2.5 2.5 0 0 1-3.535 0a2.5 2.5 0 0 1 0-3.535M12 10v4");
}

</style>

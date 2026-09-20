<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln4qfpd7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-wrap-24-filled" {...props}></Icon>
<style>
:global(.ln4qfpd7o) {
  fill: currentColor;
  d: path("M2 6a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m1 11a1 1 0 1 0 0 2h6a1 1 0 1 0 0-2zm12.414 0H19a2 2 0 1 0 0-4H3a1 1 0 1 1 0-2h16a4 4 0 0 1 0 8h-3.586l.293.293a1 1 0 0 1-1.414 1.414l-2-2a1 1 0 0 1 0-1.414l2-2a1 1 0 0 1 1.414 1.414z");
}

</style>

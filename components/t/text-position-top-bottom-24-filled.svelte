<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpecpfs_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-position-top-bottom-24-filled" {...props}></Icon>
<style>
:global(.cpecpfs_r) {
  fill: currentColor;
  d: path("M2.75 4.75a1 1 0 0 1 1-1h16.5a1 1 0 1 1 0 2H3.75a1 1 0 0 1-1-1m0 14a1 1 0 0 1 1-1h16.5a1 1 0 1 1 0 2H3.75a1 1 0 0 1-1-1m7-7.75a2.25 2.25 0 0 1 4.5 0v4.75a1 1 0 1 0 2 0V11a4.25 4.25 0 0 0-8.5 0v4.75a1 1 0 1 0 2 0z");
}

</style>

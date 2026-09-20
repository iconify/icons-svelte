<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c62a4_05o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:tidal-logo-fill" {...props}></Icon>
<style>
:global(.c62a4_05o) {
  fill: currentColor;
  d: path("m253.66 101.66l-36 36a8 8 0 0 1-11.32 0l-36-36l-.34-.38l-.34.38L135.31 136l34.35 34.34a8 8 0 0 1 0 11.32l-36 36a8 8 0 0 1-11.32 0l-36-36a8 8 0 0 1 0-11.32L120.69 136l-34.35-34.34l-.34-.38l-.34.38l-36 36a8 8 0 0 1-11.32 0l-36-36a8 8 0 0 1 0-11.32l36-36a8 8 0 0 1 11.32 0l36 36l.34.38l.34-.38l36-36a8 8 0 0 1 11.32 0l36 36l.34.38l.34-.38l36-36a8 8 0 0 1 11.32 0l36 36a8 8 0 0 1 0 11.32");
}

</style>

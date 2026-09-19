<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn-vzhbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-view-agenda" {...props}></Icon>
<style>
:global(.mn-vzhbwb) {
  fill: currentColor;
  d: path("M3 13h18v8H3zM3 3h18v8H3z");
}

</style>

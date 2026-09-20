<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ldyc6hb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:sport-cricket-ball-16-filled" {...props}></Icon>
<style>
:global(.ldyc6hb4d) {
  fill: currentColor;
  d: path("M8 1a6.99 6.99 0 0 1 5.831 3.128A.5.5 0 0 0 13.5 4h-1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 .476-.646a7 7 0 0 1-11.074 8.441A.5.5 0 0 0 3 12.5v-1a.5.5 0 0 0-1 0v.105A7 7 0 0 1 8 1M4.5 12a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m2 1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m2 1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m2 1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5");
}

</style>

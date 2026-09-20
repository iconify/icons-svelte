<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qa5halb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:sliders-horizontal-light" {...props}></Icon>
<style>
:global(.qa5halb7a) {
  fill: currentColor;
  d: path("M40 86h34.6a30 30 0 0 0 58.8 0H216a6 6 0 0 0 0-12h-82.6a30 30 0 0 0-58.8 0H40a6 6 0 0 0 0 12m64-24a18 18 0 1 1-18 18a18 18 0 0 1 18-18m112 108h-18.6a30 30 0 0 0-58.8 0H40a6 6 0 0 0 0 12h98.6a30 30 0 0 0 58.8 0H216a6 6 0 0 0 0-12m-48 24a18 18 0 1 1 18-18a18 18 0 0 1-18 18");
}

</style>

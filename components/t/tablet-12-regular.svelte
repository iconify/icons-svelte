<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="omb70c9pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:tablet-12-regular" {...props}></Icon>
<style>
:global(.omb70c9pl) {
  fill: currentColor;
  d: path("M5 7a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zM2.5 2A1.5 1.5 0 0 0 1 3.5v5A1.5 1.5 0 0 0 2.5 10h7A1.5 1.5 0 0 0 11 8.5v-5A1.5 1.5 0 0 0 9.5 2zM2 3.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5h-7a.5.5 0 0 1-.5-.5z");
}

</style>

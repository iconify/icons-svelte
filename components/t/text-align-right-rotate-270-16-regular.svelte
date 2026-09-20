<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p9jeyebvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-right-rotate-270-16-regular" {...props}></Icon>
<style>
:global(.p9jeyebvp) {
  fill: currentColor;
  d: path("M3.5 11a.5.5 0 0 1-.5-.5v-9a.5.5 0 0 1 1 0v9a.5.5 0 0 1-.5.5m4 4a.5.5 0 0 1-.5-.5v-13a.5.5 0 0 1 1 0v13a.5.5 0 0 1-.5.5m4-8a.5.5 0 0 1-.5-.5v-5a.5.5 0 0 1 1 0v5a.5.5 0 0 1-.5.5");
}

</style>

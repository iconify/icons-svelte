<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s2xj16bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-right-rotate-90-16-regular" {...props}></Icon>
<style>
:global(.s2xj16bdn) {
  fill: currentColor;
  d: path("M12.5 5a.5.5 0 0 1 .5.5v9a.5.5 0 0 1-1 0v-9a.5.5 0 0 1 .5-.5m-4-4a.5.5 0 0 1 .5.5v13a.5.5 0 0 1-1 0v-13a.5.5 0 0 1 .5-.5m-4 8a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5");
}

</style>

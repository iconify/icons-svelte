<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ltb1v9bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:step-16-filled" {...props}></Icon>
<style>
:global(.ltb1v9bqq) {
  fill: currentColor;
  d: path("M9 3a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v8.5a2.5 2.5 0 0 1-2.5 2.5H2a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h3V7a1 1 0 0 1 1-1h3z");
}

</style>

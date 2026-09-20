<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i15u0bb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-right-rotate-270-16-filled" {...props}></Icon>
<style>
:global(.i15u0bb2x) {
  fill: currentColor;
  d: path("M3.75 11a.75.75 0 0 1-.75-.75v-8.5a.75.75 0 0 1 1.5 0v8.5a.75.75 0 0 1-.75.75m4 4a.75.75 0 0 1-.75-.75V1.75a.75.75 0 0 1 1.5 0v12.5a.75.75 0 0 1-.75.75m4-8a.75.75 0 0 1-.75-.75v-4.5a.75.75 0 0 1 1.5 0v4.5a.75.75 0 0 1-.75.75");
}

</style>

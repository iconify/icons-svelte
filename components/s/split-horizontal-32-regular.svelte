<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y3hfjsbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:split-horizontal-32-regular" {...props}></Icon>
<style>
:global(.y3hfjsbje) {
  fill: currentColor;
  d: path("M3 15a1 1 0 1 0 0 2h26a1 1 0 1 0 0-2zm5 11.5v-8H6v8A3.5 3.5 0 0 0 9.5 30h13a3.5 3.5 0 0 0 3.5-3.5v-8h-2v8a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 8 26.5m18-13v-8A3.5 3.5 0 0 0 22.5 2h-13A3.5 3.5 0 0 0 6 5.5v8h2v-8A1.5 1.5 0 0 1 9.5 4h13A1.5 1.5 0 0 1 24 5.5v8z");
}

</style>

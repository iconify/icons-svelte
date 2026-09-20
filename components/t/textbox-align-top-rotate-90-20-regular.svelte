<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pgt4bdbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:textbox-align-top-rotate-90-20-regular" {...props}></Icon>
<style>
:global(.pgt4bdbza) {
  fill: currentColor;
  d: path("M13.5 6a.5.5 0 0 1 .5.5v7a.5.5 0 0 1-1 0v-7a.5.5 0 0 1 .5-.5m-2.5.5a.5.5 0 0 0-1 0v7a.5.5 0 0 0 1 0zm6 8a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3h9A2.5 2.5 0 0 1 17 5.5zm-1 0v-9A1.5 1.5 0 0 0 14.5 4h-9A1.5 1.5 0 0 0 4 5.5v9A1.5 1.5 0 0 0 5.5 16h9a1.5 1.5 0 0 0 1.5-1.5");
}

</style>

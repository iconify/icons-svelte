<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqj6lj1ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:system-24-regular" {...props}></Icon>
<style>
:global(.eqj6lj1ec) {
  fill: currentColor;
  d: path("M4.75 5h14.5A2.75 2.75 0 0 1 22 7.75v8.5A2.75 2.75 0 0 1 19.25 19H4.75A2.75 2.75 0 0 1 2 16.25v-8.5A2.75 2.75 0 0 1 4.75 5m0 1.5c-.69 0-1.25.56-1.25 1.25v8.5c0 .69.56 1.25 1.25 1.25h14.5c.69 0 1.25-.56 1.25-1.25v-8.5c0-.69-.56-1.25-1.25-1.25z");
}

</style>

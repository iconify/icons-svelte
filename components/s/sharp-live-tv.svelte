<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb5om0b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-live-tv" {...props}></Icon>
<style>
:global(.pb5om0b0m) {
  fill: currentColor;
  d: path("M23 6h-9.59l3.29-3.29L16 2l-4 4l-4-4l-.71.71L10.59 6H1v16h22zm-2 14H3V8h18zM9 10v8l7-4z");
}

</style>

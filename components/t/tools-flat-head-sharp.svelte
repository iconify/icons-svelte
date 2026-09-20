<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw7ov776y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tools-flat-head-sharp" {...props}></Icon>
<style>
:global(.sw7ov776y) {
  fill: currentColor;
  d: path("M8 21v-2h8v2zm0-3l-1-7l2-8h6l2 8l-1 7zm1.3-8h5.4l-1.25-5h-2.9z");
}

</style>

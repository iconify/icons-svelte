<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki1f0pvph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-stop" {...props}></Icon>
<style>
:global(.ki1f0pvph) {
  fill: currentColor;
  d: path("M6 6h12v12H6z");
}

</style>

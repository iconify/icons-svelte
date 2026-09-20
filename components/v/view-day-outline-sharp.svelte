<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwl_lt3ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-day-outline-sharp" {...props}></Icon>
<style>
:global(.cwl_lt3ia) {
  fill: currentColor;
  d: path("M3 20v-2h18v2zm0-4V8h18v8zm2-2h14v-4H5zM3 6V4h18v2zm2 8v-4z");
}

</style>

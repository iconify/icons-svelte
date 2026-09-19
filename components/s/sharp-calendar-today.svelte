<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfrw_dbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-calendar-today" {...props}></Icon>
<style>
:global(.bfrw_dbmt) {
  fill: currentColor;
  d: path("M22 3h-3V1h-2v2H7V1H5v2H2v20h20zm-2 18H4V8h16z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1e94tbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:shades-sharp" {...props}></Icon>
<style>
:global(.u1e94tbzt) {
  fill: currentColor;
  d: path("M4 20.98V4H3V3h18v1h-1v17q-2.061 0-3.655-1.24t-1.954-3.26H9.584q-.368 2-1.958 3.24T4 20.98m5.73-5.48h4.54V4H9.73z");
}

</style>

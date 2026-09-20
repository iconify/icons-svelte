<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o4r_8rbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:snooze-20-regular" {...props}></Icon>
<style>
:global(.o4r_8rbga) {
  fill: currentColor;
  d: path("M10.5 4a.5.5 0 0 0 0 1h4.028l-4.435 6.21a.5.5 0 0 0 .407.79h5a.5.5 0 0 0 0-1h-4.028l4.435-6.21A.5.5 0 0 0 15.5 4zm-6 6a.5.5 0 0 0 0 1h2.96l-3.35 4.188A.5.5 0 0 0 4.5 16h4a.5.5 0 0 0 0-1H5.54l3.35-4.188A.5.5 0 0 0 8.5 10z");
}

</style>

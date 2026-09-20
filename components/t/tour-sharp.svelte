<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl1wsnbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tour-sharp" {...props}></Icon>
<style>
:global(.wl1wsnbfk) {
  fill: currentColor;
  d: path("M5 22V2h2v2h14l-2 5l2 5H7v8zm8.913-11.587Q14.5 9.825 14.5 9t-.587-1.412T12.5 7t-1.412.588T10.5 9t.588 1.413T12.5 11t1.413-.587");
}

</style>

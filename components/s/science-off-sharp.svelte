<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf42eb7nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:science-off-sharp" {...props}></Icon>
<style>
:global(.cf42eb7nf) {
  fill: currentColor;
  d: path("m15 12.175l-6-6V5H7V3h10v2h-2zM19.8 22.6L18.2 21H5q-1.275 0-1.812-1.137t.262-2.113l5.2-6.3L1.4 4.2l1.4-1.4l18.4 18.4z");
}

</style>

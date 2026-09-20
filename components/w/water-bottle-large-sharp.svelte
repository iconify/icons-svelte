<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu-ew2bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:water-bottle-large-sharp" {...props}></Icon>
<style>
:global(.xu-ew2bqk) {
  fill: currentColor;
  d: path("M5 22v-6h2v-5H5V5h5V4H9V2h6v2h-1v1h5v6h-2v5h2v6z");
}

</style>

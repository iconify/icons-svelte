<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to1p8wbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stay-current-portrait-outline-sharp" {...props}></Icon>
<style>
:global(.to1p8wbjv) {
  fill: currentColor;
  d: path("M5 23V1h14v22H5Zm2-5h10V6H7v12Zm0 3h10v-1H7v1ZM7 4h10V3H7v1Zm0 0V3v1Zm0 17v-1v1Z");
}

</style>

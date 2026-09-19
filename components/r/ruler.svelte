<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wd35dktxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ruler" {...props}></Icon>
<style>
:global(.wd35dktxn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.578 29.985L29.908 5.5l12.514 12.36L17.937 42.5zM31.775 14.39l-5.428-5.307m-.353 8.157l-3.967-3.809m1.143 9.619l-5.427-5.307m-3.398 14.188l-5.428-5.307m8.239-.489l-3.967-3.81");
}

</style>

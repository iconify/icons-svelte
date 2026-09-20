<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mx0kys2xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:top-panel-open-outline-sharp" {...props}></Icon>
<style>
:global(.mx0kys2xx) {
  fill: currentColor;
  d: path("m12 15.596l3.173-3.192H8.827zM5 8h14V5H5zm0 11h14V9H5zM5 8V5zM4 20V4h16v16z");
}

</style>

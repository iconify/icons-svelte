<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu5ioprzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:toolbar-outline-sharp" {...props}></Icon>
<style>
:global(.tu5ioprzj) {
  fill: currentColor;
  d: path("M4 20V4h16v16zM5 8h14V5H5zm14 1H5v10h14zM5 8v1zm0 0V5zm0 1v10z");
}

</style>

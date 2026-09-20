<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crd57u6lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:thumbnail-bar-outline-sharp" {...props}></Icon>
<style>
:global(.crd57u6lx) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm6-1h11V6H9zm-1 0V6H4v12zm-4 0V6zm4 0h1zM8 6h1z");
}

</style>

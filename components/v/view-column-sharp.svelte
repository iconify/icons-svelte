<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq220ihex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-column-sharp" {...props}></Icon>
<style>
:global(.uq220ihex) {
  fill: currentColor;
  d: path("M4 18V6h4.825v12zm5.594 0V6H14.4v12zm5.575 0V6h4.825v12z");
}

</style>

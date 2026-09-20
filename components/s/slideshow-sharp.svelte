<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cba9kcbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:slideshow-sharp" {...props}></Icon>
<style>
:global(.cba9kcbbh) {
  fill: currentColor;
  d: path("M9.885 15.577L15.462 12L9.885 8.423zM4 20V4h16v16z");
}

</style>

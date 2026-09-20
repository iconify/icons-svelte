<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j71r3vb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:splitscreen-landscape-outline-sharp" {...props}></Icon>
<style>
:global(.j71r3vb-o) {
  fill: currentColor;
  d: path("M13 16h5V8h-5zm-7 0h5V8H6zm-4 4V4h20v16zm18-2V6H4v12zM4 6v12z");
}

</style>

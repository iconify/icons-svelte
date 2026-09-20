<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w08u_jb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:screenshot-outline-sharp" {...props}></Icon>
<style>
:global(.w08u_jb6x) {
  fill: currentColor;
  d: path("M16 15h-2v3h-3v2h5zM8 9h2V6h3V4H8zM5 23V1h14v5.1h1v4.8h-1V23zm2-2h10V3H7zm0 0V3z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iflytvbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:web-stories-sharp" {...props}></Icon>
<style>
:global(.iflytvbnd) {
  fill: currentColor;
  d: path("M17 20V4h2v16zM2 22V2h13v20zm19-4V6h1.5v12z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi9wkcbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-2-bar-sharp" {...props}></Icon>
<style>
:global(.yi9wkcbtj) {
  fill: currentColor;
  d: path("M3 21L21 3v18zm9.289-1H20V5.427l-7.711 7.712z");
}

</style>

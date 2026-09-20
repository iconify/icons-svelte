<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2p6r_ejb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-4-bar-sharp" {...props}></Icon>
<style>
:global(.b2p6r_ejb) {
  fill: currentColor;
  d: path("M3 21L21 3v18z");
}

</style>

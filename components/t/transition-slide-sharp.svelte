<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx-4-jprb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:transition-slide-sharp" {...props}></Icon>
<style>
:global(.kx-4-jprb) {
  fill: currentColor;
  d: path("M2 19V5h5.039v14zm7.423 0V5H22v14z");
}

</style>

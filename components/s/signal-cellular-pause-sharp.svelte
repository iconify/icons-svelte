<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxpg_bx2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-pause-sharp" {...props}></Icon>
<style>
:global(.nxpg_bx2g) {
  fill: currentColor;
  d: path("M2 22L22 2v11h-9v9zm17 0v-7h2v7zm-4 0v-7h2v7z");
}

</style>

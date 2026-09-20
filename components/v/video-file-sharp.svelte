<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqmfklxnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:video-file-sharp" {...props}></Icon>
<style>
:global(.jqmfklxnd) {
  fill: currentColor;
  d: path("M4 22V2h10l6 6v14zm9-13h5l-5-5zm-5 9h6v-2l2 1.05v-4.1L14 14v-2H8z");
}

</style>

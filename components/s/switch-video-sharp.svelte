<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jphbgg36o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:switch-video-sharp" {...props}></Icon>
<style>
:global(.jphbgg36o) {
  fill: currentColor;
  d: path("m7.98 14.808l.709-.708l-1.6-1.6h6.784l-1.6 1.6l.708.708L15.788 12l-2.807-2.808l-.708.708l1.6 1.6H7.089l1.6-1.6l-.708-.708L5.173 12zM3.48 19V5h14v6.27l3.04-3.04v7.54l-3.04-3.04V19z");
}

</style>

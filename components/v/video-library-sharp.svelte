<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhou5kbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:video-library-sharp" {...props}></Icon>
<style>
:global(.jhou5kbdz) {
  fill: currentColor;
  d: path("M11.5 13.577L17.077 10L11.5 6.423zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ugpmvqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-nightlight-round" {...props}></Icon>
<style>
:global(.s2ugpmvqv) {
  fill: currentColor;
  d: path("M15.5 22c1.05 0 2.05-.16 3-.46c-4.06-1.27-7-5.06-7-9.54s2.94-8.27 7-9.54c-.95-.3-1.95-.46-3-.46c-5.52 0-10 4.48-10 10s4.48 10 10 10");
}

</style>

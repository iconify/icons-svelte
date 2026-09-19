<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifp2n7k6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-get-app" {...props}></Icon>
<style>
:global(.ifp2n7k6a) {
  fill: currentColor;
  d: path("M19 9h-4V3H9v6H5l7 7zM5 18v2h14v-2z");
}

</style>

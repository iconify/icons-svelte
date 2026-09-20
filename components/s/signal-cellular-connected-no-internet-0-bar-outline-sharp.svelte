<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bszd1dm9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-connected-no-internet-0-bar-outline-sharp" {...props}></Icon>
<style>
:global(.bszd1dm9o) {
  fill: currentColor;
  d: path("M3 21L21 3v4.23h-1V5.422L5.421 20H17.5v1zm17-3.23V9.615h1v8.153zm1.23 2v1.46h-1.46v-1.46z");
}

</style>

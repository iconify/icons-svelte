<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4go4xb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:subnet-fill-sharp" {...props}></Icon>
<style>
:global(.h4go4xb3x) {
  fill: currentColor;
  d: path("M13 7.829V10h8a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1h8V7.829a3 3 0 1 1 2 0M7 15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm5 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm5.01 0H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>

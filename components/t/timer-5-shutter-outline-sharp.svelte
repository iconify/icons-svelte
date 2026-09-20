<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiyyuwygu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:timer-5-shutter-outline-sharp" {...props}></Icon>
<style>
:global(.kiyyuwygu) {
  fill: currentColor;
  d: path("M8 19v-3h6v-2.5H8V5h9v3h-6v2.5h6V19z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udax7gwxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:splitscreen-top-outline-sharp" {...props}></Icon>
<style>
:global(.udax7gwxi) {
  fill: currentColor;
  d: path("M3 11V3h18v8zm0 10v-8h18v8zm2-2h14v-4H5z");
}

</style>

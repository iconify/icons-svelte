<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvzsccbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-decrease-sharp" {...props}></Icon>
<style>
:global(.vvzsccbuf) {
  fill: currentColor;
  d: path("M1 19L6.25 5h2.5L14 19h-2.4l-1.275-3.575h-5.65L3.4 19zm4.4-5.6h4.2L7.55 7.6h-.1zM15 13v-2h8v2z");
}

</style>

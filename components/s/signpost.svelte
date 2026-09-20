<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxqhbubvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signpost" {...props}></Icon>
<style>
:global(.dxqhbubvv) {
  fill: currentColor;
  d: path("M11 22v-4H6l-3-3l3-3h5v-2H4V4h7V2h2v2h5l3 3l-3 3h-5v2h7v6h-7v4z");
}

</style>

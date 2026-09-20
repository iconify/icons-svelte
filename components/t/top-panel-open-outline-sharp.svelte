<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7endep0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:top-panel-open-outline-sharp" {...props}></Icon>
<style>
:global(.h7endep0l) {
  fill: currentColor;
  d: path("m12 16.5l4-4H8zM5 8h14V5H5zm0 11h14v-9H5zM5 8V5zM3 21V3h18v18z");
}

</style>

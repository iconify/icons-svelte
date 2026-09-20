<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttpw3gb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:unknown-med-outline-sharp" {...props}></Icon>
<style>
:global(.ttpw3gb6h) {
  fill: currentColor;
  d: path("M2 13v-3h9v3zm11 0v-3h9v3z");
}

</style>

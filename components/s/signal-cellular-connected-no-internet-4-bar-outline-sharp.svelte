<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klinfuimz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-connected-no-internet-4-bar-outline-sharp" {...props}></Icon>
<style>
:global(.klinfuimz) {
  fill: currentColor;
  d: path("M2 22L22 2v6h-4v14zm18-4v-8h2v8zm0 4v-2h2v2z");
}

</style>

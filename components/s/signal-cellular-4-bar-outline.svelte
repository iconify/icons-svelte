<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt4e-oebs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-4-bar-outline" {...props}></Icon>
<style>
:global(.jt4e-oebs) {
  fill: currentColor;
  d: path("M2 22L22 2v20z");
}

</style>

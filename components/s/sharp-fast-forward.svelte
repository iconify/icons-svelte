<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-qenbb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-fast-forward" {...props}></Icon>
<style>
:global(.t-qenbb4q) {
  fill: currentColor;
  d: path("m4 18l8.5-6L4 6zm9-12v12l8.5-6z");
}

</style>

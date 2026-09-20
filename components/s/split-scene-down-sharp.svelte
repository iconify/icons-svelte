<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1g2yxbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-down-sharp" {...props}></Icon>
<style>
:global(.p1g2yxbvr) {
  fill: currentColor;
  d: path("M4 9V3h16v6zm0 12v-8H2v-2h20v2h-2v8z");
}

</style>

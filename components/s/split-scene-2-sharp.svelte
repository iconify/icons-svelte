<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3qy9xntt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-2-sharp" {...props}></Icon>
<style>
:global(.o3qy9xntt) {
  fill: currentColor;
  d: path("M4 21v-6h16v6zm-2-8v-2h2V3h16v8h2v2z");
}

</style>

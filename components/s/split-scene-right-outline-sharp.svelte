<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg38sezga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:split-scene-right-outline-sharp" {...props}></Icon>
<style>
:global(.gg38sezga) {
  fill: currentColor;
  d: path("M4 19V5h5.116v1H5v12h4.116v1zm7.5 2V3h1v2H20v14h-7.5v2zM5 18V6z");
}

</style>

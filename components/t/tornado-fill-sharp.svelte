<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzkuasbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tornado-fill-sharp" {...props}></Icon>
<style>
:global(.mzkuasbkk) {
  fill: currentColor;
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m3 4h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m3 4h10a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m1 4h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2m1 4a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

</style>

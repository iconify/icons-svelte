<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nu8gwy0th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-1-bar-outline-sharp" {...props}></Icon>
<style>
:global(.nu8gwy0th) {
  fill: currentColor;
  d: path("M2 22L22 2v20zm8-2h10V6.85l-10 10z");
}

</style>

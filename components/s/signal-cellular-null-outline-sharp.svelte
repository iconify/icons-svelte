<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeyzhjsft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-null-outline-sharp" {...props}></Icon>
<style>
:global(.zeyzhjsft) {
  fill: currentColor;
  d: path("M2 22L22 2v20zm4.825-2H20V6.85z");
}

</style>

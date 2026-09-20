<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea0uyzmhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:transition-slide-sharp" {...props}></Icon>
<style>
:global(.ea0uyzmhg) {
  fill: currentColor;
  d: path("M1 20V4h6v16zm8 0V4h14v16z");
}

</style>

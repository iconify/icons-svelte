<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6h4uzxif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-off-sharp" {...props}></Icon>
<style>
:global(.c6h4uzxif) {
  fill: currentColor;
  d: path("M20.987 22.408L19.579 21H3l8.292-8.292L3.65 5.07l.708-.713L21.7 21.7zM21 18.2l-7.6-7.6L21 3z");
}

</style>

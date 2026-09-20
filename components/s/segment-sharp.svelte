<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohmkwdbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:segment-sharp" {...props}></Icon>
<style>
:global(.ohmkwdbaz) {
  fill: currentColor;
  d: path("M10 17.27v-1h10v1zm0-4.77v-1h10v1zM4 7.73v-1h16v1z");
}

</style>

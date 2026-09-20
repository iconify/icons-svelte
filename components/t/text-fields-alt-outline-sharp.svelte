<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxz_g4lxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-fields-alt-outline-sharp" {...props}></Icon>
<style>
:global(.gxz_g4lxm) {
  fill: currentColor;
  d: path("M2 21v-2h20v2zm17-4V3h1.5v14zM4 17L9.25 3h2.5L17 17h-2.4l-1.25-3.6H7.7L6.4 17zm4.4-5.6h4.2l-2.05-5.8h-.1z");
}

</style>

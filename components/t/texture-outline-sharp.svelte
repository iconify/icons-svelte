<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="favijcu8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:texture-outline-sharp" {...props}></Icon>
<style>
:global(.favijcu8e) {
  fill: currentColor;
  d: path("M3.075 20.925v-1.4l16.45-16.45h1.425v1.4L4.475 20.925zM3 14.7v-2.8L11.9 3h2.8zM3 7V3h4zm14 14l4-4v4zm-7.7 0L21 9.3v2.8L12.1 21z");
}

</style>

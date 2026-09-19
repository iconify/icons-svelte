<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_pw6tbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-branding-watermark" {...props}></Icon>
<style>
:global(.z_pw6tbco) {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-2 16h-9v-6h9z");
}

</style>

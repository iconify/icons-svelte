<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp6t8obxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:voicemail-fill-sharp" {...props}></Icon>
<style>
:global(.tp6t8obxz) {
  fill: currentColor;
  d: path("M9.465 14h5.07A4.002 4.002 0 0 1 20 8.536A4 4 0 0 1 18 16H6a4.001 4.001 0 1 1 3.465-2");
}

</style>

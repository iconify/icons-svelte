<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccpu6-tvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tilt-arrow-up-sharp" {...props}></Icon>
<style>
:global(.ccpu6-tvp) {
  fill: currentColor;
  d: path("M3 20L6.616 4h10.75L21 20zm8.48-9.079v4.695h1V10.92l2.12 2.114l.708-.708L11.98 9l-3.289 3.289l.708.713z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k193bi48h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sticky-note-2-outline-sharp" {...props}></Icon>
<style>
:global(.k193bi48h) {
  fill: currentColor;
  d: path("M5 19h9v-5h5V5H5zm-1 1V4h16v10.289L14.288 20zm3.885-6.539v-1H12v1zm0-3.961v-1h8.23v1zM5 19V5z");
}

</style>

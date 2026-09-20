<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlph2zydo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sticky-note-sharp" {...props}></Icon>
<style>
:global(.zlph2zydo) {
  fill: currentColor;
  d: path("M15.577 20H4V4h16v11.577zM15 19l4-4h-4zm-3.5-3.5h1v-6h3v-1h-7v1h3z");
}

</style>

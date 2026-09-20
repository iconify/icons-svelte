<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9ldb98hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:side-navigation-outline-sharp" {...props}></Icon>
<style>
:global(.j9ldb98hx) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm8-1h7V5h-7z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6d5ja8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:scrollable-header-sharp" {...props}></Icon>
<style>
:global(.fi6d5ja8h) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14v-5.384H5z");
}

</style>

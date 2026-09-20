<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdffd6b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tab-group-sharp" {...props}></Icon>
<style>
:global(.fdffd6b5z) {
  fill: currentColor;
  d: path("M3.5 20V6.616h1V19h12.385v1zm3-3V3h14v14zm6.77-9.961h6.23V4h-6.23z");
}

</style>

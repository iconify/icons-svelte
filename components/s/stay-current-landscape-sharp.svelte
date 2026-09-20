<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivomhabac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stay-current-landscape-sharp" {...props}></Icon>
<style>
:global(.ivomhabac) {
  fill: currentColor;
  d: path("M2 18V6h20v12zm3.5-1h13V7h-13z");
}

</style>

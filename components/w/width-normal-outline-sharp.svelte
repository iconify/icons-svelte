<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4x7fzbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:width-normal-outline-sharp" {...props}></Icon>
<style>
:global(.h4x7fzbii) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h4.673V6H4zm5.673 0h4.654V6H9.673zm5.654 0H20V6h-4.673zM9.673 6v12z");
}

</style>

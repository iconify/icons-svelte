<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4qfs0b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:space-bar-outline-sharp" {...props}></Icon>
<style>
:global(.p4qfs0b5c) {
  fill: currentColor;
  d: path("M5 14V9h1v4h12V9h1v5z");
}

</style>
